# Crashlytics: Quality First

## Brian Swift - @bswift - 19 Feb 2015

The apps foundations are defined by how stable the app is.
Does not matter what you do with ads or login if the app is not stable.

FACT: All apps crash.

One star reviews on your app suck. Wouldn't it be nice to be able to address these user issues?

When a crash happens they store the data on the crash on the device. On the next app launch they send the crash data up to the server.

Once on the server they analyse the crash to extract version, line number, file, device meta data. They then group the crashes for reporting on numbers of occurrence etc.

Today Twitter are processing 8k crashes every second on their platform.
The key is dev tools that are easy and quick to use for developers.

Strava moved from another crash report tool over to Crashlytics.
Strave had a bug that 3-4% of users were experiencing, which is huge. With Crashlytics they found the issue and fixed it.


Once they had a good crash report tool, Crashlytics then focused on extending the product to be a good beta testing tool. Crashlytics Beta.

Session length is a nice metric in Answers.

Because Answers is realtime, runkeeper rolled out an update only 2 hours after a new app version launch. They saw how things were not working quickly and were able to take steps to fix it!

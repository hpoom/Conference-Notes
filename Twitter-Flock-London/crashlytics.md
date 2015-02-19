# Crashlytics: Quality First

## Brian Swift - @bswift - 19 Feb 2015 - ??:00

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




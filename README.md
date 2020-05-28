# House Automator Comrade App for Android

_Unofficial fork of the Home Assistant companion app without Google services._

Home Assistant and the companion app are awesome,
but they require proprietary services that are not available
on custom Android OSes like [LineageOS](https://lineageos.org/).
So, a version without those services is necessary.

The developers of the official app
[have no interest in maintaining such a version
themselves](https://github.com/home-assistant/home-assistant-android/issues/42#issuecomment-584372676),
and [have suggested forking the project](https://github.com/home-assistant/home-assistant-android/issues/42#issuecomment-560160840) instead.

This is such a fork.

## Warning

_USE AT YOUR OWN RISK_. I'm not sure how up-to-date I can keep this fork.

## The plan

1. **DONE** Remove proprietary services from the code,
   making sure the missing things are handled correctly.
2. **DONE** Change the branding to prevent <https://github.com/home-assistant/home-assistant-android/issues/42#issuecomment-584212855>
3. Publish to [F-Droid](https://f-droid.org/)
4. _(optional)_ Replace the missing functionality by FOSS alternatives,
   like those mentioned in <https://github.com/home-assistant/home-assistant-android/issues/42#issuecomment-581090179>

## Branching

The `master` branch of this fork is not based on the original repository
and only contains meta stuff like this README,
and later maybe stuff not related to a specific version of the app like scripts
and icons.

The actual app code is produced by creating a branch from an upstream version
tag and applying the necessary changes.
The following branches are available:

* [1.8.0](https://github.com/jleeuwes/home-assistant-android-without-google/tree/1.8.0-without-google)


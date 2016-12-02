# Awesome AutoValue Extensions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> :shipit: A curated list of awesome AutoValue extensions

*Please read the [contribution guidelines](.github/CONTRIBUTING.md) before contributing.*

**Check out my [blog](https://medium.com/@blipinsk) :coffee: or say *hi* on [Twitter](https://twitter.com/blipinsk).**

## Serialization
* [auto-value-gson](https://github.com/rharter/auto-value-gson) - Creating [Gson](https://github.com/google/gson) `TypeAdapterFactory`.
* [auto-value-moshi](https://github.com/rharter/auto-value-moshi) - Creating [Moshi](https://github.com/square/moshi) `JsonAdapterFactory`.
* [AutoJackson](https://github.com/bgogetap/AutoJackson) - Helps with [Jackson](https://github.com/FasterXML/jackson) serialization/deserialization.
* [auto-value-parcel](https://github.com/rharter/auto-value-parcel) - Implementing Android [`Parcelable`](https://developer.android.com/reference/android/os/Parcelable.html) interface automatically.

## Database
* [auto-value-cursor](https://github.com/gabrielittner/auto-value-cursor) - Creating objects from Android [`Cursor`](https://developer.android.com/reference/android/database/Cursor.html).
* [auto-value-firebase](https://github.com/mattlogan/auto-value-firebase) - Creating [Firebase Realtime Database](https://firebase.google.com/docs/database/) objects.
* [auto-value-result-set](https://github.com/workarounds/auto-value-result-set) - Creating objects from [ResultSet](https://docs.oracle.com/javase/7/docs/api/java/sql/ResultSet.html).

## Default methods
* [auto-value-redacted](https://github.com/square/auto-value-redacted) - Omitting selected fields from `toString()`.
* [auto-value-neuter-tostring](https://github.com/agatti/auto-value-neuter-tostring) - Simplifying `toString()` output to `[class_name]@[hex_hashcode]`.
* [auto-value-ignore-hash-equals](https://github.com/REggar/auto-value-ignore-hash-equals) -  Omitting selected fields from `hashcode()` and `equals()`.

## Special methods
* [auto-value-map](https://github.com/cynnyx/auto-value-map) - Generating a Map with fields as keys and associated values as fields' values.
* [auto-value-querymap](https://github.com/oguzbabaoglu/auto-value-querymap) - Generating a Map that can be used with Retrofit's [`@QueryMap`](https://square.github.io/retrofit/2.x/retrofit/index.html?retrofit2/http/QueryMap.html).

  > This extension works similar to the `auto-value-map`. The differences are:
  >
  > 1. `auto-value-map` creates `Map<String, Object>` while this one creates `Map<String, String>`
  > 2. In `auto-value-querymap` you can use `@Param` annotation to specify a different key (to be used in Map) for a particular field.
* [auto-value-with](https://github.com/gabrielittner/auto-value-with) - Generating methods prefixed with "with".

## Tools
* [auto-value-extension-util](https://github.com/gabrielittner/auto-value-extension-util) - Utilities for writing extensions.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Bartek Lipinski](https://github.com/blipinsk) has waived all copyright and related or neighboring rights to this work.

<!--
1. Data interaction
    * gabrielittner/auto-value-cursor
    * mattlogan/auto-value-firebase
    * workarounds/auto-value-result-set
2. Serializers/Deserializers
    * rharter/auto-value-gson
    * rharter/auto-value-moshi
    * bgogetap/AutoJackson
3. Collection
    * cynnyx/auto-value-map
4. Android specific
    * rharter/auto-value-parcel
5. Library-specific
    * oguzbabaoglu/auto-value-querymap
    * m-zagorski/auto-value-base-adapter-item
6. Methods modification/generation
    * agatti/auto-value-neuter-tostring
    * square/auto-value-redacted
    * REggar/auto-value-ignore-hash-equals
    * gabrielittner/auto-value-with
-->

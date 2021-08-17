MaximumUpgradeLanguages.cmake
=============================


Just maximally upgrades C++ and C languages versions.

Unfortunately, CMake doesn't have values for `CMAKE_*_STANDARD` that force it to use the latest standard available in compiler.

Call `maximum_upgrade_*_version` to upgrade a single language only, and `maximum_upgrade_languages_versions` to upgrade all the languages.

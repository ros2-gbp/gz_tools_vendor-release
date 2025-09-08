^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gz_tools_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.2.1 (2025-09-08)
------------------
* Jetty support: minor updates (`#9 <https://github.com/gazebo-release/gz_tools_vendor/issues/9>`_)
  * Add option VENDOR_FROM_LIB_VCS_REF
  This allows vendoring from a specified vcs ref instead
  of the hard-coded tag. When this option is set to true,
  a branch, tag, or commit can be specified in the
  LIB_VCS_REF variable. If LIB_VCS_REF is unspecified,
  vendoring will use gz-tools2.
  * 2.0.3
  ---------
* Contributors: Steve Peters

0.2.0 (2025-09-04)
------------------
* Bump version to 2.0.3 (`#12 <https://github.com/gazebo-release/gz_tools_vendor/issues/12>`_)
* Contributors: Carlos Agüero

0.1.2 (2025-02-05)
------------------
* Bump version to 2.0.2 (`#8 <https://github.com/gazebo-release/gz_tools_vendor/issues/8>`_)
* Contributors: Addisu Z. Taddese

0.1.1 (2024-10-29)
------------------
* Disallow rubocop dependency (`#4 <https://github.com/gazebo-release/gz_tools_vendor/issues/4>`_)
* Add support for prerelease suffixes (`#2 <https://github.com/gazebo-release/gz_tools_vendor/issues/2>`_)
* Contributors: Addisu Z. Taddese

0.1.0 (2024-04-23)
------------------
* Use an alias target for root library
* Contributors: Addisu Z. Taddese

0.0.3 (2024-04-10)
------------------
* Add support for the `<pkg>::<pkg>` and `<pkg>::all` targets, fix sourcing of dsv files
* Contributors: Addisu Z. Taddese

0.0.2 (2024-03-28)
------------------
* Update vendored package version
* Require calling find_package on the underlying package
* Fix linter (`#1 <https://github.com/gazebo-release/gz_tools_vendor/issues/1>`_)
* Initial import
* Contributors: Addisu Z. Taddese

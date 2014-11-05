ColorSharp's Changelog
======================

## 2014-11-05 : 0.7.0 Release

### Contributors
 * Andrés Correa Casablanca <castarco@gmail.com , castarco@litipk.com>

### Changes
 * Improved XML documentation.
 * Removed many build warnings (related with XML documentation).
 * Sealed many classes.
 * Big refactor:
   * Removed the colors conversion path search mechanism.
   * Now is less flexible, but more efficient and simple.
   * Now it's better to use the non type-parametric conversion methods.
   * **WARNING:** Now we assume that Y=1 in CIE's xyY or XYZ color spaces is the luminance of the white point.
   * **WARNING:** Breaks API.

### Bugfixes
 * Bugfix in sRGB->CIE's 1931 XYZ conversion (the gamma correction was done after the lineal transformation)


## 2014-11-05 : 0.6.0 Release

### Contributors
 * Andrés Correa Casablanca <castarco@gmail.com , castarco@litipk.com>

### Changes
 * Improved XML documentation.
 * Removed many build warnings (related with XML documentation)
 * Sealed many classes.
 * Removed unused properties from CIExyY class.
 * Split project into ColorSharp and ColorSharpTests.
 * Removed NUnit dependency.

### Bugfixes
 * Bugfix in sRGB->CIE's 1931 XYZ conversion (the gamma correction was done after the lineal transformation)
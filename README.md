# page-navigation
A clone of GitHub's project navigation to illustrate accessible page navigation patterns

## Points of reference

* why it it shouldn't be skipped
* `nav` landmark
  * `aria-label` to name landmark
* `ul`
  * offer count of links
  * `aria-labelledby` to link to nav label
  * `lyst-style-type: none` removes the double motion
* `a` links
  * `aria-current="page"`
* `svg`
  * `aria-hidden`
* "augmenter"
  * `.visually-hidden`
  * `aria-hidden`
# :bulb: Remember Mini Man
[![License][licensesvg]][license] <br />
This is a simple board game using memory. <br />
<a href='https://play.google.com/store/apps/details?id=me.blog.korn123.rememberminiman'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width="323" height="125"/></a><br />
[README of Korean][README_ko.md]

# How to play
```
Step1. Remember Miniman in order.
       stage1: 3 Miniman
       stage2: 5 Miniman
       stage3: 8 Miniman
```
<img src="screenshots/memorize_1.gif" width="288" height="512">&nbsp;
<img src="screenshots/memorize_2.png" width="288" height="512">&nbsp;
<img src="screenshots/memorize_3.png" width="288" height="512">

```
Step2. Choose Miniman in order.
```
<img src="screenshots/play_1.png" width="288" height="512">&nbsp;
<img src="screenshots/play_2.png" width="288" height="512">


```
Step3. Repeat to stage three.
       The final record is the sum of the elapsed times of all stages.
       I will use the firebase database to provide the ranking later.
```
<img src="screenshots/play_3.png" width="288" height="512">&nbsp;
<img src="screenshots/play_4.png" width="288" height="512">&nbsp;
<img src="screenshots/play_5.png" width="288" height="512">&nbsp;

# How to build
```
Step1. Fork or download 'remember-miniman' project.
Step2. Import 'remember-miniman' project into android studio.
Step3. Use below link download svg images from Flaticon.
Step4. Choose 20 svg images of your liking and change the file name as below.
       ex> miniman_1.svg, miniman_2.svg, ..., miniman_19.svg, miniman_20.svg
Step5. Copy the 20 renamed files to the '/app/src/main/res/raw' directory.
Step6. Build 'remember-miniman' project with android studio.
```
[Download miniman svg images from Flaticon][1]

# License
[LICENSE][LICENSE.md]


[1]: https://www.flaticon.com/packs/miniman
[licensesvg]: https://img.shields.io/badge/License-Apache--2.0-brightgreen.svg
[license]: https://github.com/hanjoongcho/remember-miniman/blob/master/LICENSE.md
[README_ko.md]: https://github.com/hanjoongcho/remember-miniman/blob/master/README_ko.md
[LICENSE.md]: https://github.com/hanjoongcho/remember-miniman/blob/master/LICENSE.md
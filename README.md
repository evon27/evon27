![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90)

HTML:

<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=capsule%20render&fontSize=90" />

Types

Type data makes to change Background Image.

    wave : default
    egg
    shark
    slice
    rect
    soft
    rounded
    cylinder
    waving
    transparent

Write &type= on the URL

![header](https://capsule-render.vercel.app/api?type=slice)

Color

Change Background Image!

    &color=auto : Proven random color. List are here
    &color=timeAuto : Proven random color, but is decided by time.
    &color=random : Really random color. I don't know what colors are showing.
    &color=gradient : Proven random gradient. List are here
    &color=timeGradient : Proven random gradient, but is decided by time.
    &color=_hexcode : default(#B897FF)
    &color=_custom_gradient : Custom gradient. If write as &color=0:EEFF00,100:a82da8, it will be converted to { 0%: 'EEFF00', 100%: 'a82da8' }. (e.g. DEMO)

If you use auto mode. no need to change fontColor. auto also change fontColor auto.

![header](https://capsule-render.vercel.app/api?color=auto)

    If you use static color. Do not write '#'

    When use timeAuto and timeGradient?

    Used section header and footer at the same time.

Custom Color List

You can customize the list of colors that will appear randomly only for &color=auto and &color=gradient.

Write &customColorList= on the URL.

    If you use &color=auto, look at pallete list.
    If you use &color=gradient, look at gradient list.

Pick the color patterns you want and remember the idx value.

For example, if the idx values ​​are 0, 2, and 3, write: &customColorList=0,2,3

If you want to make many apperances of idx=2, you can write them repeatedly. (e.g. &customColorList=0,2,2,2,2,3)

![header](https://capsule-render.vercel.app/api?color=gradient&customColorList=0,2,2,5,30)

Section

Section data makes reverse Background Image.

    &section=header : (default)
    &section=footer

Write &section= on the URL

![footer](https://capsule-render.vercel.app/api?section=footer)

Reversal

Reverse the image left and right. (Color at the same time)

    &reversal=false : (default)
    &reversal=true

![reversal](https://capsule-render.vercel.app/api?type=slice&reversal=true&color=gradient)

Height

Change Image Size. Default value is 120.

Write &height= on the URL

![header](https://capsule-render.vercel.app/api?height=400)

    Do not write px

Text

Input text over the Image.

Write Something &text= .

![header](https://capsule-render.vercel.app/api?text=Hello%World!)

    You can't use some Special Characters. Like '#', '&', '/' ...

    It makes confused API

    It is recommended to use %20 (blank) only

Desc

Input desc over the Image.

Write Something &desc= .

![header](https://capsule-render.vercel.app/api?height=400&text=Hello%20World!&desc=Hello%20capsule%20render)

    You can't use some Special Characters. Like '#', '&', '/' ...

    It makes confused API

    It is recommended to use %20 (blank) only

Text Background

Background of Text.

Write &textBg=true to active.

    If you want to increase background-size, add %20 between text values. This is because background-size depends on the length of the english-text. (%20 means spacing)

![header](https://capsule-render.vercel.app/api?type=rounded&color=gradient&text=%20asdf%20&height=300&fontSize=100&textBg=true)

Text Animation

Make the text dynamic.

Write &animation= , if you want to use.

    fadeIn : fadeIn 1.2s
    scaleIn : scaleIn .8s
    blink : blink .6s
    blinking : blinking 1.6s
    twinkling : twinkling 4s

![header](https://capsule-render.vercel.app/api?text=capsule_render&animation=fadeIn)

FontColor

Change text color. Default value is 000000 Value should be Hex code with erased '#'

Write &fontColor= behind Text query

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontColor=d6ace6)

FontSize

Change text font size. Default value is 70.

Write &fontSize= behind Text query

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontSize=40)

    Do not write px

FontAlign

Change text horizontal-align (x). write number between 0~100

&fontAlign= : Default value is 50. center of image

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontAlign=70)

FontAlignY

Change text vertical-align (y). write number between 0~100

&fontAlignY= : Default value is 50. center of image

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontAlignY=20)

DescSize

Change desc font size. Default value is 20.

Write &descSize= behind desc query

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontSize=40&desc=Desc&descSize=30)

    Do not write px

DescAlign

Change desc horizontal-align (x). write number between 0~100

&descAlign= : Default value is 50. center of image

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontAlign=70&desc=Desc&descAlign=20)

DescAlignY

Change text vertical-align (y). write number between 0~100

&descAlignY= : Default value is 60. center of image

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontAlignY=20&desc=Desc&descAlignY=40)

Rotate

Usage &rotate= , to rotate text.

You can also use negative number.

    Recommend number arrange. ☞ 0 ~ 360, 0 ~ -360.

![header](https://capsule-render.vercel.app/api?text=Hello%World!&fontSize=20&rotate=-30)

Demo
Wave

wave
Egg

egg
Shark

shark
Slice

slice
Rect

rect
Soft

soft
Rounded

rounded
Cylinder

cylinder
Waving

waving
Transparent

transparent
Things that helped contribute

    SVG Path Easy Maker Codepen
    SVG Path draw mavo.io

footer
About

🌈 Dynamic Coloful Image Render
github.com/kyechan99/capsule-render#demo
Topics
github github-profile image-generator dynamic-profile readme-generator profile-readme
Resources
Readme
License
MIT License
Stars
353 stars
Watchers
5 watching
Forks
219 forks
Contributors 3

    @kyechan99
    kyechan99 Ye-Chan Kang
    @yehwankim23
    yehwankim23 김예환 Ye-Hwan Kim (Sam)
    @dependabot[bot]
    dependabot[bot]

Environments 2

Production Active

    Preview Active

Languages

JavaScript 100.0%

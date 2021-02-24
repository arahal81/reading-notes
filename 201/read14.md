# Read 14

## Transforms
* With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size position, and change elements. All of these new techniques are made possible by the transform property.
* The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

* Transform Syntax
`div { -webkit-transform: scale(1.5); -moz-transform: scale(1.5); -o-transform: scale(1.5); transform: scale(1.5);}`
* 2D Transforms: Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.
* 2D Scale: Using the scale value within the transform property allows you to change the appeared size of an element.
* Transform Origin: As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically.
1. Fade in
`                                                                                                                                       .fade{                                                                                                                                                                                                                                                                      opacity:0.5;                                                                                                                            }                                                                                                                                                                                                                                                                                .fade:hover{                                                                                                                                       opacity:1;                                                                                                                              }`
2. Change color `.color:hover { background:#53a7ea;  }`

3. Grow & Shrink `.grow:hover { -webkit-transform: scale(1.3);    -ms-transform: scale(1.3);   transform: scale(1.3); }`

4. Rotate elements`.rotate:hover { -webkit-transform: rotateZ(-30deg);  -ms-transform: rotateZ(-30deg);   transform: rotateZ(-30deg); }`

5. Square to circle  `.circle:hover  {  border-radius:50%; } `
6. 3D shadow `.threed:hover { box-shadow: 1px 1px #53a7ea,  2px 2px #53a7ea, 3px 3px #53a7ea; -webkit-transform: translateX(-3px); transform: translateX(-3px);  }`
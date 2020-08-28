# FTroulette使用说明

<a name="gY99j"></a>
## Example
To run the example project, clone the repo, and run `pod install` from the Example directory first.
<a name="VfdAw"></a>
## Requirements
<a name="eHz2z"></a>
## Installation
FTroulette is available through [CocoaPods](https://cocoapods.org/). To install it, simply add the following line to your Podfile:<br />pod 'FTroulette'
<a name="f5hox"></a>
## Principle
1.以触碰点P与圆心O1为起始边，对±θ角范围内的刻度线进行偏移。角θ可根据三角形O1O2A，利用余弦定理，已知三边求角：a=r，b=R，c=R-d 代入即可求得α，即θ<br />[![](https://github.com/Takemoto-xie/resource/raw/master/roulette/%E4%BD%99%E5%BC%A6%E5%AE%9A%E7%90%86.svg#align=left&display=inline&height=50&margin=%5Bobject%20Object%5D&originHeight=50&originWidth=189&status=done&style=none&width=189)](https://github.com/Takemoto-xie/resource/blob/master/roulette/%E4%BD%99%E5%BC%A6%E5%AE%9A%E7%90%86.svg)<br />[![](https://github.com/Takemoto-xie/resource/raw/master/roulette/roulette1.png#align=left&display=inline&height=477&margin=%5Bobject%20Object%5D&originHeight=477&originWidth=600&status=done&style=none&width=600)](https://github.com/Takemoto-xie/resource/blob/master/roulette/roulette1.png)<br />2.原刻度线ab，偏移后得到新刻度线a'b'，新刻度线的位置L，可根据三角形O1O2a'，利用余弦定理结合完全平方公式，已知两边和一角求第三边：∠γ=∠α-∠β，a=R-d，c=r 代入即可求得b，即L<br />[![](https://github.com/Takemoto-xie/resource/raw/master/roulette/%E4%BD%99%E5%BC%A6%E5%AE%9A%E7%90%862.svg#align=left&display=inline&height=27&margin=%5Bobject%20Object%5D&originHeight=27&originWidth=213&status=done&style=none&width=213)](https://github.com/Takemoto-xie/resource/blob/master/roulette/%E4%BD%99%E5%BC%A6%E5%AE%9A%E7%90%862.svg)<br />[![](https://github.com/Takemoto-xie/resource/raw/master/roulette/roulette2.png#align=left&display=inline&height=497&margin=%5Bobject%20Object%5D&originHeight=497&originWidth=600&status=done&style=none&width=600)](https://github.com/Takemoto-xie/resource/blob/master/roulette/roulette2.png)
<a name="f0UKR"></a>
## Demo
[![](https://github.com/Takemoto-xie/resource/raw/master/roulette/demo.gif#align=left&display=inline&height=652&margin=%5Bobject%20Object%5D&originHeight=652&originWidth=320&status=done&style=none&width=320)](https://github.com/Takemoto-xie/resource/blob/master/roulette/demo.gif)<br />
<br />![timg.gif](https://cdn.nlark.com/yuque/0/2020/gif/414848/1598584884060-24a8e22f-81e9-4a2f-bf0d-7d2e0648b778.gif#align=left&display=inline&height=220&margin=%5Bobject%20Object%5D&name=timg.gif&originHeight=220&originWidth=220&size=157921&status=done&style=none&width=220)<br />![37f3cc3a9709fd6bf69109d92b433aa4.gif](https://cdn.nlark.com/yuque/0/2020/gif/414848/1598586308745-5eb15852-08e7-4e5b-bdec-6de32c9dc36d.gif#align=left&display=inline&height=1080&margin=%5Bobject%20Object%5D&name=37f3cc3a9709fd6bf69109d92b433aa4.gif&originHeight=1080&originWidth=1920&size=3078013&status=done&style=none&width=1920)![81f0cf59b3cbfc06c1dbf9159a342b45.gif](https://cdn.nlark.com/yuque/0/2020/gif/414848/1598586326289-406e3ea0-5ded-4a7b-8f61-1aaca70881b5.gif#align=left&display=inline&height=400&margin=%5Bobject%20Object%5D&name=81f0cf59b3cbfc06c1dbf9159a342b45.gif&originHeight=400&originWidth=580&size=623051&status=done&style=none&width=580)![65776da21aec6cf93421e41483b6a1a0.gif](https://cdn.nlark.com/yuque/0/2020/gif/414848/1598586329135-efa77ba9-a3bd-4e00-a91c-a0a157422d3b.gif#align=left&display=inline&height=480&margin=%5Bobject%20Object%5D&name=65776da21aec6cf93421e41483b6a1a0.gif&originHeight=480&originWidth=480&size=601635&status=done&style=none&width=480)
<a name="UFtms"></a>
## Author
[794751446@qq.com](mailto:794751446@qq.com), [1085192695@qq.com](mailto:1085192695@qq.com)
<a name="de3la"></a>
## License
FTroulette is available under the MIT license. See the LICENSE file for more info.<br />


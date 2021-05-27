# Description
This is just a static solution to generate a one link that redirects users to download the target app from the appropriate store based on phone type.
### Supported Stores: 
<table>
    <tbody>
        <tr>
            <td rowspan=2>Android</td>
            <td rowspan=1>HUAWEI AppGallery</td>
        </tr>
        <tr>
            <td>Google Play Store</td>
        </tr>
        <tr>
            <td rowspan=2>iPhone</td>
            <td>App Store</td>
        </tr>
    </tbody>
</table>

Note
> This solution can be used as a reference to build many dynamic based cases. For example, you can add an endpoint that asks for the app's Android package name and App Store link as parameters and returns a shortcut link that redirects the user to the appropriate store based based on the parameters.

# Demo Example
- Android phone without Google Play Services (only AppGallery):

https://user-images.githubusercontent.com/61454003/119883998-14977780-bf28-11eb-8be5-5eefc61790ea.mp4

- Android phone with Both Google Play Services and HUAWEI Mobile Services (AppGallery & Play Store):


https://user-images.githubusercontent.com/61454003/119884425-88d21b00-bf28-11eb-86c3-5bafac78ff65.mp4


- iPhone (App Store):

https://user-images.githubusercontent.com/61454003/119884287-604a2100-bf28-11eb-8f68-d5c3e349644b.mp4


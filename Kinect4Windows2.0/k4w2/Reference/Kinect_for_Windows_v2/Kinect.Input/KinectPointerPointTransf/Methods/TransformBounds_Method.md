KinectPointerPointTransform.TransformBounds Method  
==================================================  

Transforms the specified bounding box and returns an axis-aligned bounding box that is exactly large enough to contain it. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public:  
Rect TransformBounds(  
         Rect rect  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public Rect TransformBounds (  
         Rect rect  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var rect = kinectPointerPointTransform.transformBounds(rect);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*rect*    
Type: [Rect](http://msdn.microsoft.com/en-us/library/windows.foundation.rect.aspx)  
The bounding box to transform.  

<span id="ID4EP"></span>
#### Return value  

Type: [Rect](http://msdn.microsoft.com/en-us/library/windows.foundation.rect.aspx)  
 The smallest axis-aligned bounding box possible that contains the transformed rect.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[KinectPointerPointTransform Class](../../KinectPointerPointTransf.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TransformBounds Method
RLTitle : KinectPointerPointTransform.TransformBounds Method
KeywordK : TransformBounds method
KeywordK : KinectPointerPointTransform.TransformBounds method
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPointTransform.TransformBounds
KeywordF : KinectPointerPointTransform.TransformBounds
KeywordF : TransformBounds
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPointTransform.TransformBounds(Windows.Foundation.Rect)
KeywordA : M:WindowsPreview.Kinect.Input.KinectPointerPointTransform.TransformBounds(Windows.Foundation.Rect)
AssetID : M:WindowsPreview.Kinect.Input.KinectPointerPointTransform.TransformBounds(Windows.Foundation.Rect)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPointerPointTransform.TransformBounds
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->

cccc# Flutter Ace Snippet

Flutter Ace Snippet is collection of best snippets for flutter devs. Once you use it, fall in love with Flutter Ace. We Developed `Easiest & Best snippets` available in market. It supports Provider and GetX as well.

---
> CODE SMARTLY TO MAKE YOUR LIFE EASY
---

## Features
- Write code with 10X speed
- It is `Easiest & Best snippets` available in market.
- Required parameter will autocomplete
- Supports complax widgets (Eg. PageView.builder, CustomPainter and Controllers for Getx & Provider)

## Snippets
- We have huge amount of snippets for flutter.
- We divide our all snippents in category, Given below
    1. **Create New Flutter App** (Eg. newFlutterApp, newFlutterAppProvider)
    1. **Import Statement** (Eg. material package)
    1. **Basic Widget Snippets** (Eg. Container, Row, Column)
    1. **Builders Widget Snippets** (Eg. GridView.builder, PageView.builder)
    1. **Advance Widget Snippets** (Eg. CustomClipper, CustomPainter)
    1. **Margin & Padding Snippets** (Eg. EdgeInsets.method())
    1. **Widget's Properties & Var Declaration Snippets** (Eg. height, width, List\<E\>)
    1. **Provider Snippets** (Eg. Consumer, ChangeNotifier Controller)
    1. **Getx Snippents** (Eg. GetXController, Bindings)

<br>

| Create New Flutter App ||
------------ | ----------- 
**Prefix** | **Description**
newFlutterApp | Initial Flutter App
newFlutterAppProvider | Initial Flutter App With Provider
newFlutterAppGet | Initial Flutter App With GetX 

| Import Statement ||
------------ | ----------- 
**Prefix** | **Code**
imm | import 'package:flutter/material.dart';
imc | import 'package:flutter/cupertino.dart';
imGet | import 'package:get/get.dart';
imProvider | import 'package:provider/provider.dart';

| Basic Widget Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
container | Gives Container Widgets | Container(<br>&nbsp; child: Text("Container"),<br>)
row | Gives Row Widgets | <code>Row(<br>&nbsp;crossAxisAlignment: CrossAxisAlignment.center,<br> &nbsp;mainAxisAlignment: MainAxisAlignment.start,<br>&nbsp;children: [],<br>)</code>
col | Gives Column Widgets | <code>Column(<br>&nbsp;crossAxisAlignment: CrossAxisAlignment.center,<br>&nbsp;mainAxisAlignment: MainAxisAlignment.start,<br>&nbsp;children: [],<br>)</code>
text | Gives Text Widget | <code>Text(<br>&nbsp;"Text",<br>&nbsp;style: TextStyle(),<br>)</code>
scsv | Gives SingleChildScrollView Widget | <code>SingleChildScrollView(<br>&nbsp;child: Container(),<br>)</code>
gd | Gives GestureDetector Widget with onTap Method | <code>GestureDetector(<br>&nbsp;onTap: (){<br>&nbsp;<br>&nbsp;},<br>&nbsp;child: Container(),<br>)</code>
sb | Gives SizedBox widget with width & height | <code>SizedBox(<br>&nbsp;height: 0,<br>&nbsp;width: 0,<br>&nbsp;child: Container(),<br>)</code>
sbw | Gives SizedBox widget with width only | <code>SizedBox(<br>&nbsp;width: 0,<br>&nbsp;child: Container(),<br>)</code>
sbh | Gives SizedBox widget with height only | <code>SizedBox(<br>&nbsp;height: 0,<br>&nbsp;child: Container(),<br>)</code>
imgA | Gives Image.asset() method with height & width | <code>Image.asset(<br>&nbsp;"assets/filename",<br>&nbsp;width: 0,<br>&nbsp;height: 0,<br>)</code>
imgN | Gives Image.network() method with height & width | <code>Image.network(<br>&nbsp;"URL",<br>&nbsp;width: 0,<br>&nbsp;height: 0,<br>)</code>
imgF | Gives Image.file() method with height & width | <code>Image.network(<br>&nbsp;fileObject,<br>&nbsp;width: 0,<br>&nbsp;height: 0,<br>)</code>
navigatorPush | Gives Navigator.push() with initial structure | <code>Navigator.push(<br>&nbsp;context,<br>&nbsp;MaterialPageRoute(<br>&nbsp;&nbsp;builder: (context) => MyHomePage(),<br>&nbsp;),<br>);</code>
navigatorPop | Gives a Navigator.pop() method | <code>Navigator.pop(context);</code>
navigatorPushName | Gives Navigator.pushNamed method with initial parameter |<code>Navigator.pushNamed(context, "/myHomePage");</code>

| Builders Widget Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
lvBuild | Gives a ListView.builder with initial properties | <code>ListView.builder(<br>&nbsp;itemCount: 0,<br>&nbsp;shrinkWrap: true,<br>&nbsp;scrollDirection: Axis.vertical,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;&nbsp;return Text("ListView.builder");<br>&nbsp;},<br>)</code>
lvSeparated | Gives a ListView.separated with initial properties | <code>ListView.separated(<br>&nbsp;itemCount: 0,<br>&nbsp;shrinkWrap: true,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;&nbsp;return Text("ListView.separated");<br>&nbsp;},<br>&nbsp;separatorBuilder: (context, index) {<br>&nbsp;&nbsp;return Divider(<br>&nbsp;&nbsp;&nbsp;height: 2,<br>&nbsp;&nbsp;&nbsp;color: Colors.grey,<br>&nbsp;&nbsp;);<br>&nbsp;},<br>)</code>
gvBuild | Gives a GridView.builder with initial properties | <code>GridView.builder(<br>&nbsp;gridDelegate: SliverGridDelegateWithFixedCrossAxisCount(crossAxisCount: 3),<br>&nbsp;itemCount: 0,<br>&nbsp;shrinkWrap: true,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;&nbsp;return Text("GridView.Builder");<br>&nbsp;},<br>)</code>
gvCount | Gives a GridView.count with initial properties | <code>GridView.count(<br>&nbsp;crossAxisCount: 3,<br>&nbsp;shrinkWrap: true,<br>&nbsp;children: \[<br>&nbsp;&nbsp;Text("Gridview.count"),<br>&nbsp;\],<br>)</code>
gvExtent | Gives a GridView.extent with initial properties | <code>GridView.extent(<br>&nbsp;maxCrossAxisExtent: 100,<br>&nbsp;shrinkWrap: true,<br>&nbsp;children: \[<br>&nbsp;&nbsp;Text("Gridview.extent"),<br>&nbsp;\],<br>)</code>
pvBuild | Gives a PageView.builder with initial structure | <code>PageView.builder(<br>&nbsp;itemCount: 3,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;return Container(<br>&nbsp;&nbsp;margin: EdgeInsets.symmetric(horizontal: 10, vertical: 10),<br>&nbsp;&nbsp;decoration: BoxDecoration(<br>&nbsp;&nbsp;&nbsp;color: Colors.purple,<br>&nbsp;&nbsp;&nbsp;borderRadius: BorderRadius.circular(10),<br>&nbsp;&nbsp;),<br>&nbsp;&nbsp;child: Text(<br>&nbsp;&nbsp;&nbsp;&nbsp;"PageView",<br>&nbsp;&nbsp;&nbsp;&nbsp;style: TextStyle(color: Colors.white),<br>&nbsp;&nbsp;&nbsp;),<br>&nbsp;&nbsp;);<br>&nbsp;},<br>)</code>
streamBuild | Gives a StreamBuilder with initial properties | StreamBuilder(<br>&nbsp;stream: stream,<br>&nbsp;initialData: initalData,<br>&nbsp;builder: (BuildContext context, AsyncSnapshot snapshot) {<br>&nbsp;&nbsp;&nbsp;return Text("Stream Builder");<br>&nbsp;},<br>)</code>
animatedBuild | Gives a AnimatedBuilder with initial properties | <code>AnimatedBuilder(<br>&nbsp;animation: animation,<br>&nbsp;child: child,<br>&nbsp;builder: (context, child) {<br>&nbsp;&nbsp;return Text("Animated Builder");<br>&nbsp;},<br>)</code>
layoutBuild | Gives a LayoutBuilder with initial properties | <code>LayoutBuilder(<br>&nbsp;builder: (BuildContext context, BoxConstraints constraints) {<br>&nbsp;&nbsp;return Text("Layout Builder");<br>&nbsp;},<br>)</code>
futureBuild | Gives a FutureBuilder with initial properties | <code>FutureBuilder(<br>&nbsp;future: future,<br>&nbsp;initialData: initialData,<br>&nbsp;builder: (context, snapshot) {<br>&nbsp;&nbsp;return Text("Future Builder");<br>&nbsp;},<br>)</code>
tweenBuild | Gives a TweenAnimationBuilder with initial properties | <code>TweenAnimationBuilder(<br>&nbsp;duration: const Duration(),<br>&nbsp;tween: Tween(),<br>&nbsp;builder: (BuildContext context, dynamic value, Widget? child) {<br>&nbsp;&nbsp;return Text("Tween Animation Builder");<br>&nbsp;},<br>),</code>

| Advance Widget Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
cClipper | Gives a class that exetnds CustomClipper with override method | <code> import 'package:flutter/cupertino.dart';<br>class NameClipper extends CustomClipper<Path> {<br><br>&nbsp;@override<br>&nbsp;Path getClip(Size size) {<br>&nbsp;&nbsp;// TODO: implement getClip<br>&nbsp;&nbsp;throw UnimplementedError();<br>&nbsp;}<br><br>&nbsp;bool shouldReclip(covariant CustomClipper<Path> oldClipper) => false;<br>} </code>
cPainter | Gives a class that exetnds CustomPainter with override method | <code> import 'package:flutter/material.dart';<br>class namePainter extends CustomPainter {<br><br>&nbsp;@override<br>&nbsp;void paint(Canvas canvas, Size size) {<br><br>&nbsp;}<br>&nbsp;@override<br>&nbsp;bool shouldRepaint(namePainter oldDelegate) => false;<br><br>&nbsp;@override<br>&nbsp;bool shouldRebuildSemantics(namePainter oldDelegate) => false;<br>} </code>

| Margin & Padding Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
padAll &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Gives a padding property with EdgeInsets.All() method with inital parameter | <code>padding: EdgeInsets.all(8),</code> 
padLTRB | Gives a padding property with EdgeInsets.fromLTRB() method with inital parameter | <code>padding: EdgeInsets.fromLTRB(left, top, right, bottom),</code>
padSym | Gives a padding property with EdgeInsets.symmetric() method with inital parameter | <code>padding: EdgeInsets.symmetric(horizontal: 0, vertical: 0),</code>
padOnly | Gives a padding property with EdgeInsets.only() method | <code>padding: EdgeInsets.only(),</code>
marAll | Gives a margin property with EdgeInsets.All() method with inital parameter | <code>margin: EdgeInsets.all(8),</code> 
marLTRB | Gives a margin property with EdgeInsets.fromLTRB() method with inital parameter | <code>margin: EdgeInsets.fromLTRB(left, top, right, bottom),</code>
marSym | Gives a margin property with EdgeInsets.symmetric() method with inital parameter | <code>margin: EdgeInsets.symmetric(horizontal: 0, vertical: 0),</code>
marOnly | Gives a margin property with EdgeInsets.only() method | <code>margin: EdgeInsets.only(),</code>

| Widget's Properties & Var Declaration Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
width | Gives width property with MediaQuery Width | width: MediaQuery.of(context).size.width,
height | Gives height property with MediaQuery Width | height: MediaQuery.of(context).size.height,
brAll | Gives borderRadius property with BorderRadius.all() method | borderRadius: BorderRadius.all(Radius.circular(10)),
brCircular | Gives borderRadius property with BorderRadius.circular() method | borderRadius: BorderRadius.circular(10),
colorHax | Gives color property with Color object initial argument | color: Color(0xFF9C27B0),
list | Gives a List with initial assignment | <code>List<String> listName = \[<br><br>\];</code>

| Provider Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
changeNotiFier | Gives a class that extends ChangeNotifier with one demo variable | <code>import 'package:flutter/material.dart';<br><br>class MySchedule extends ChangeNotifier {<br>&nbsp;int _count = 0;<br><br>&nbsp;int get count => _count;<br><br>&nbsp;set count(int value) {<br>&nbsp;&nbsp;_count = value;<br>&nbsp;&nbsp;notifyListeners();<br>&nbsp;}<br>}</code>
consumer | Gives Consumer widget with initial properties | <code>Consumer<T>(<br>&nbsp;builder: (context, value, child) {<br>&nbsp;&nbsp;return Text("Provider Consumer");<br>&nbsp;},<br>)</code>

| Get Snippets |||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
getController | Gives a class that extends GetxController with one demo variable | <code>import 'package:get/get.dart';<br><br>class NameController extends GetxController {<br>&nbsp;var number = 0.obs;<br>&nbsp;void changeValue(val) => number.value = val;<br>}</code>
getBinding | Gives a class that extends Bindings with override method | <code>import 'package:get/get.dart';<br><br>class HomeBindings extends Bindings {<br><br>&nbsp;@override<br>&nbsp;void dependencies() {<br>&nbsp;&nbsp;Get.put<Controller1>(Controller1());<br>&nbsp;}<br>}</code>
getBuilder | Gives GetBuilder widgets with initial properties | <code>GetBuilder<Controller>(<br>&nbsp;init: Controller(),<br>&nbsp;builder: (controller) {<br>&nbsp;&nbsp;return Text("Get Builder");<br>&nbsp;},<br>)</code>
getX | Gives GetX widgets with initial properties | <code>GetX<Controller>(<br>&nbsp;init: Controller(),<br>&nbsp;builder: (controller) {<br>&nbsp;&nbsp;return Text("GetX");<br>&nbsp;},<br>)</code>
mixingBuilder | Gives MixinBuilder widgets with initial properties | <code>MixinBuilder<Controller>(<br>&nbsp;init: Controller(),<br>&nbsp;builder: (controller) {<br>&nbsp;&nbsp;return Text("Mixing Builder");<br>&nbsp;},<br>)</code>
gWidth | Gives width property with Get Width | width: Get.size.width,
gHeight | Gives height property with Get Width | height: Get.size.height,

## Supports
1. `MacOs`, `Windows` & `Linux`
1. VScode version: `^1.54.0`
## Known Issues
If you will find any issue in extension then feel free to generate issue and you can make PR as well.
## Release Notes
### 1.0.0

Initial release of `Flutter Ace Snippet`

---

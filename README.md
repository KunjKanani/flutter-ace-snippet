# Flutter Ace Snippet

Flutter Ace Snippet is a collection of the best snippets for flutter devs. Once you use it, fall in love with Flutter Ace. We Developed `Easiest & Best snippets` available in the market. It supports Provider and GetX as well.

---
> CODE SMARTLY TO MAKE YOUR LIFE EASY
---

## Features
- Write code with `10X` speed
- It is `Easiest & Best snippets` available in the market.
- `Required parameter` will autocomplete
- Supports `complex widgets` (Eg. PageView.builder, CustomPainter and Controllers for Getx & Provider)
- `Proper tabs positions` for speed up coding

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
`newFlutterApp` | Initial Flutter App
`newFlutterAppProvider` | Initial Flutter App With Provider
`newFlutterAppGet` | Initial Flutter App With GetX 

| Import Statement ||
------------ | ----------- 
**Prefix** | **Code**
`imm` | import 'package:flutter/material.dart';
`imc` | import 'package:flutter/cupertino.dart';
`imGet` | import 'package:get/get.dart';
`imProvider` | import 'package:provider/provider.dart';

|| Basic Widget Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`container` | It will give Container Widgets | Container(<br>&nbsp; child: Text("Container"),<br>)
`row` | It will give Row Widgets | Row(<br>&nbsp;crossAxisAlignment: CrossAxisAlignment.center,<br> &nbsp;mainAxisAlignment: MainAxisAlignment.start,<br>&nbsp;children: [],<br>)
`col` | It will give Column Widgets | Column(<br>&nbsp;crossAxisAlignment: CrossAxisAlignment.center,<br>&nbsp;mainAxisAlignment: MainAxisAlignment.start,<br>&nbsp;children: [],<br>)
`text` | It will give Text Widget | Text(<br>&nbsp;"Text",<br>&nbsp;style: TextStyle(),<br>)
`scsv` | It will give SingleChildScrollView Widget | SingleChildScrollView(<br>&nbsp;child: Container(),<br>)
`gd` | It will give GestureDetector Widget with onTap Method | GestureDetector(<br>&nbsp;onTap: (){<br>&nbsp;<br>&nbsp;},<br>&nbsp;child: Container(),<br>)
`sb` | It will give SizedBox widget with width & height | SizedBox(<br>&nbsp;height: 0,<br>&nbsp;width: 0,<br>&nbsp;child: Container(),<br>)
`sbw` | It will give SizedBox widget with width only | SizedBox(<br>&nbsp;width: 0,<br>&nbsp;child: Container(),<br>)
`sbh` | It will give SizedBox widget with height only | SizedBox(<br>&nbsp;height: 0,<br>&nbsp;child: Container(),<br>)
`imgA` | It will give Image.asset() method with height & width | Image.asset(<br>&nbsp;"assets/filename",<br>&nbsp;width: 0,<br>&nbsp;height: 0,<br>)
`imgN` | It will give Image.network() method with height & width | Image.network(<br>&nbsp;"URL",<br>&nbsp;width: 0,<br>&nbsp;height: 0,<br>)
`imgF` | It will give Image.file() method with height & width | Image.network(<br>&nbsp;fileObject,<br>&nbsp;width: 0,<br>&nbsp;height: 0,<br>)
`navigatorPush` | It will give Navigator.push() with initial structure | Navigator.push(<br>&nbsp;context,<br>&nbsp;MaterialPageRoute(<br>&nbsp;&nbsp;builder: (context) => MyHomePage(),<br>&nbsp;),<br>);
`navigatorPop` | It will give a Navigator.pop() method | Navigator.pop(context);
`navigatorPushName` | It will give Navigator.pushNamed method with initial parameter |Navigator.pushNamed(context, "/myHomePage");

|| Builders Widget Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`lvBuild` | It will give a ListView.builder with initial properties | ListView.builder(<br>&nbsp;itemCount: 0,<br>&nbsp;shrinkWrap: true,<br>&nbsp;scrollDirection: Axis.vertical,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;&nbsp;return Text("ListView.builder");<br>&nbsp;},<br>)
`lvSeparated` | It will give a ListView.separated with initial properties | ListView.separated(<br>&nbsp;itemCount: 0,<br>&nbsp;shrinkWrap: true,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;&nbsp;return Text("ListView.separated");<br>&nbsp;},<br>&nbsp;separatorBuilder: (context, index) {<br>&nbsp;&nbsp;return Divider(<br>&nbsp;&nbsp;&nbsp;height: 2,<br>&nbsp;&nbsp;&nbsp;color: Colors.grey,<br>&nbsp;&nbsp;);<br>&nbsp;},<br>)
`gvBuild` | It will give a GridView.builder with initial properties | GridView.builder(<br>&nbsp;gridDelegate: SliverGridDelegateWithFixedCrossAxisCount(crossAxisCount: 3),<br>&nbsp;itemCount: 0,<br>&nbsp;shrinkWrap: true,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;&nbsp;return Text("GridView.Builder");<br>&nbsp;},<br>)
`gvCount` | It will give a GridView.count with initial properties | GridView.count(<br>&nbsp;crossAxisCount: 3,<br>&nbsp;shrinkWrap: true,<br>&nbsp;children: \[<br>&nbsp;&nbsp;Text("Gridview.count"),<br>&nbsp;\],<br>)
`gvExtent` | It will give a GridView.extent with initial properties | GridView.extent(<br>&nbsp;maxCrossAxisExtent: 100,<br>&nbsp;shrinkWrap: true,<br>&nbsp;children: \[<br>&nbsp;&nbsp;Text("Gridview.extent"),<br>&nbsp;\],<br>)
`pvBuild` | It will give a PageView.builder with initial structure | PageView.builder(<br>&nbsp;itemCount: 3,<br>&nbsp;itemBuilder: (context, index) {<br>&nbsp;return Container(<br>&nbsp;&nbsp;margin: EdgeInsets.symmetric(horizontal: 10, vertical: 10),<br>&nbsp;&nbsp;decoration: BoxDecoration(<br>&nbsp;&nbsp;&nbsp;color: Colors.purple,<br>&nbsp;&nbsp;&nbsp;borderRadius: BorderRadius.circular(10),<br>&nbsp;&nbsp;),<br>&nbsp;&nbsp;child: Text(<br>&nbsp;&nbsp;&nbsp;&nbsp;"PageView",<br>&nbsp;&nbsp;&nbsp;&nbsp;style: TextStyle(color: Colors.white),<br>&nbsp;&nbsp;&nbsp;),<br>&nbsp;&nbsp;);<br>&nbsp;},<br>)
`streamBuild` | It will give a StreamBuilder with initial properties | StreamBuilder(<br>&nbsp;stream: stream,<br>&nbsp;initialData: initalData,<br>&nbsp;builder: (BuildContext context, AsyncSnapshot snapshot) {<br>&nbsp;&nbsp;&nbsp;return Text("Stream Builder");<br>&nbsp;},<br>)
`animatedBuild` | It will give a AnimatedBuilder with initial properties | AnimatedBuilder(<br>&nbsp;animation: animation,<br>&nbsp;child: child,<br>&nbsp;builder: (context, child) {<br>&nbsp;&nbsp;return Text("Animated Builder");<br>&nbsp;},<br>)
`layoutBuild` | It will give a LayoutBuilder with initial properties | LayoutBuilder(<br>&nbsp;builder: (BuildContext context, BoxConstraints constraints) {<br>&nbsp;&nbsp;return Text("Layout Builder");<br>&nbsp;},<br>)
`futureBuild` | It will give a FutureBuilder with initial properties | FutureBuilder(<br>&nbsp;future: future,<br>&nbsp;initialData: initialData,<br>&nbsp;builder: (context, snapshot) {<br>&nbsp;&nbsp;return Text("Future Builder");<br>&nbsp;},<br>)
`tweenBuild` | It will give a TweenAnimationBuilder with initial properties | TweenAnimationBuilder(<br>&nbsp;duration: const Duration(),<br>&nbsp;tween: Tween(),<br>&nbsp;builder: (BuildContext context, dynamic value, Widget? child) {<br>&nbsp;&nbsp;return Text("Tween Animation Builder");<br>&nbsp;},<br>),

|| Advance Widget Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`cClipper` | It will give a class that exetnds CustomClipper with override method |  import 'package:flutter/cupertino.dart';<br>class NameClipper extends CustomClipper<Path> {<br><br>&nbsp;@override<br>&nbsp;Path getClip(Size size) {<br>&nbsp;&nbsp;// TODO: implement getClip<br>&nbsp;&nbsp;throw UnimplementedError();<br>&nbsp;}<br><br>&nbsp;bool shouldReclip(covariant CustomClipper<Path> oldClipper) => false;<br>} 
`cPainter` | It will give a class that exetnds CustomPainter with override method |  import 'package:flutter/material.dart';<br>class namePainter extends CustomPainter {<br><br>&nbsp;@override<br>&nbsp;void paint(Canvas canvas, Size size) {<br><br>&nbsp;}<br>&nbsp;@override<br>&nbsp;bool shouldRepaint(namePainter oldDelegate) => false;<br><br>&nbsp;@override<br>&nbsp;bool shouldRebuildSemantics(namePainter oldDelegate) => false;<br>} 

|| Margin & Padding Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`padAll` | It will give a padding property with EdgeInsets.All() method with inital parameter | padding: EdgeInsets.all(8), 
`padLTRB` | It will give a padding property with EdgeInsets.fromLTRB() method with inital parameter | padding: EdgeInsets.fromLTRB(left, top, right, bottom),
`padSym` | It will give a padding property with EdgeInsets.symmetric() method with inital parameter | padding: EdgeInsets.symmetric(horizontal: 0, vertical: 0),
`padOnly` | It will give a padding property with EdgeInsets.only() method | padding: EdgeInsets.only(),
`marAll` | It will give a margin property with EdgeInsets.All() method with inital parameter | margin: EdgeInsets.all(8), 
`marLTRB` | It will give a margin property with EdgeInsets.fromLTRB() method with inital parameter | margin: EdgeInsets.fromLTRB(left, top, right, bottom),
`marSym` | It will give a margin property with EdgeInsets.symmetric() method with inital parameter | margin: EdgeInsets.symmetric(horizontal: 0, vertical: 0),
`marOnly` | It will give a margin property with EdgeInsets.only() method | margin: EdgeInsets.only(),

|| Widget's Properties & Var Declaration Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`width` | It will give width property with MediaQuery Width | width: MediaQuery.of(context).size.width,
`height` | It will give height property with MediaQuery Width | height: MediaQuery.of(context).size.height,
`brAll` | It will give borderRadius property with BorderRadius.all() method | borderRadius: BorderRadius.all(Radius.circular(10)),
`brCircular` | It will give borderRadius property with BorderRadius.circular() method | borderRadius: BorderRadius.circular(10),
`colorHax` | It will give color property with Color object initial argument | color: Color(0xFF9C27B0),
list | It will give a List with initial assignment | List<String> listName = \[<br><br>\];

|| Provider Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`changeNotiFier` | It will give a class that extends ChangeNotifier with one demo variable | import 'package:flutter/material.dart';<br><br>class MySchedule extends ChangeNotifier {<br>&nbsp;int _count = 0;<br><br>&nbsp;int get count => _count;<br><br>&nbsp;set count(int value) {<br>&nbsp;&nbsp;_count = value;<br>&nbsp;&nbsp;notifyListeners();<br>&nbsp;}<br>}
`consumer` | It will give Consumer widget with initial properties | Consumer<T>(<br>&nbsp;builder: (context, value, child) {<br>&nbsp;&nbsp;return Text("Provider Consumer");<br>&nbsp;},<br>)

|| Get Snippets ||
----------- | ----------- | ----------- |
**Prefix** | **Description** | **Code** |
`getController` | It will give a class that extends GetxController with one demo variable | import 'package:get/get.dart';<br><br>class NameController extends GetxController {<br>&nbsp;var number = 0.obs;<br>&nbsp;void changeValue(val) => number.value = val;<br>}
`getBinding` | It will give a class that extends Bindings with override method | import 'package:get/get.dart';<br><br>class HomeBindings extends Bindings {<br><br>&nbsp;@override<br>&nbsp;void dependencies() {<br>&nbsp;&nbsp;Get.put<Controller1>(Controller1());<br>&nbsp;}<br>}
`getBuilder` | It will give GetBuilder widgets with initial properties | GetBuilder<Controller>(<br>&nbsp;init: Controller(),<br>&nbsp;builder: (controller) {<br>&nbsp;&nbsp;return Text("Get Builder");<br>&nbsp;},<br>)
`getX` | It will give GetX widgets with initial properties | GetX<Controller>(<br>&nbsp;init: Controller(),<br>&nbsp;builder: (controller) {<br>&nbsp;&nbsp;return Text("GetX");<br>&nbsp;},<br>)
`mixingBuilder` | It will give MixinBuilder widgets with initial properties | MixinBuilder<Controller>(<br>&nbsp;init: Controller(),<br>&nbsp;builder: (controller) {<br>&nbsp;&nbsp;return Text("Mixing Builder");<br>&nbsp;},<br>)
`gWidth` | It will give width property with Get Width | width: Get.size.width,
`gHeight` | It will give height property with Get Width | height: Get.size.height,

## Supports
1. `MacOs`, `Windows` & `Linux`
1. VScode version: `^1.54.0`
## Known Issues
You will find any `issue` in the extension, feel free to `generate issue and make PR` as well.
## Release Notes
### 1.0.0

The initial release of `Flutter Ace Snippet`

---

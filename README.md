import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: ContainerDemo(),
 );
 }
}
class ContainerDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('Container Widget')),
 body: Center(
 child: Container(
 padding: EdgeInsets.all(20),
 color: Colors.amber,
 child: Text(
 'Inside Container!',
 style: TextStyle(fontSize: 20),
 ),
 ),
 ),
 );
 }
}

import 'package:flutter/material.dart';

void main() {
  runApp(Homepage());
}

class Homepage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        accentColor: Colors.amberAccent,
      ),
      home: showcase(),
    );
  }
}

class showcase extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text(
          'Shakib Hasan',
        ),
        actions: <Widget>[
          IconButton(
            onPressed: () => {
              //do something
            },
            icon: Icon(
              Icons.ac_unit,
              color: Colors.black,
            ),
          ),
          IconButton(
            onPressed: () => {
              //do something
            },
            icon: Icon(
              Icons.access_alarm,
              color: Colors.black,
            ),
          ),
        ],
      ),
      body: Center(
        child: Column(
          children: [
            Text(
              'First app',
              textAlign: TextAlign.left,
            ),
             Text(
              'First app',
              textAlign: TextAlign.right,
            ),
          ],
        ),
      ),
    );
  }
}

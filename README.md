# flutter_quiz_app

This is quiz app build using flutter

my initial thought to build this app as below:

<import 'package:flutter/material.dart';

void main() {
  runApp(const myApp());
}

class myApp extends StatelessWidget {
  const myApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.deepPurple,
        body: Center(
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: [
              Image.asset(
                "assets/images/quiz-logo.png",
                height: 300,
                width: 300,
              ),
              const SizedBox(height: 50),
              const Text(
                "Learn Flutter the fun way!",
                style: TextStyle(
                    color: Colors.white,
                    fontWeight: FontWeight.normal,
                    fontSize: 24),
              ),
              const SizedBox(height: 50),
              OutlinedButton(
                onPressed: () {},
                child: const Text(
                  "Start Quiz",
                  style: TextStyle(
                    color: Colors.white,
                  ),
                ),
              ),
            ],
          ),
        ),
      ),
    );
  }
}
>

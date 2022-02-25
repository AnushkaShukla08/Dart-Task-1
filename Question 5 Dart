import 'dart:io';

void main() {
  int? units;
  stdout.write('Enter A Number');

  units = int.parse(stdin.readLineSync()!);

  if (units <= 200) {
    print(units * 0.5);
  } else if (units <= 500) {
    print((200 * 0.5) + (units - 200) * 1);
  } else if (units <= 1000) {
    print((200 * 0.5) + (300 * 1.0) + (units - 500) * 2.5);
  } else if (units <= 1500) {
    print((200 * 0.5) + (300 * 1) + (500 * 2.5) + (units - 1000) * 3.5);
  } else if (units <= 2500) {
    print((200 * 0.5) +
        (300 * 1) +
        (500 * 2.5) +
        (500 * 3.5) +
        (units - 1500) * 5);
  } else if (units > 2500) {
    print((200 * 0.5) +
        (300 * 1) +
        (500 * 2.5) +
        (500 * 3.5) +
        (1000 * 5) +
        (units - 1500) * 10);
  }
}

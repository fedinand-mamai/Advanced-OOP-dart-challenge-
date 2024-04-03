class Student {
  String name;
  int age;
  String gradeLevel;

  Student(this.name, this.age, this.gradeLevel);

  void printInfo() {
    print('Student: $name, Age: $age, Grade Level: $gradeLevel');
  }
}

class Teacher {
  String name;
  int age;
  String subject;

  Teacher(this.name, this.age, this.subject);

  void printInfo() {
    print('Teacher: $name, Age: $age, Subject: $subject');
  }
}

void main() {
  // Create student object
  Student student = Student('Magoha Matiangi', 20, 'Grade 15');
  // Create teacher object
  Teacher teacher = Teacher('Wanjiru Wamuchomba', 28, 'Engineering');

  // Print student information
  print('Student Information:');
  student.printInfo();

  // Print teacher information
  print('\nTeacher Information:');
  teacher.printInfo();
}

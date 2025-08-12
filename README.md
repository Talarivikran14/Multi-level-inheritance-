class Person {
    void read() {
        System.out.println("he can read English");
    }
}

class Students extends Person {
    void write() {
        System.out.println("students writing exams");
    }
}

class CollegeStudents extends Students {
    void coding() {
        System.out.println("btech students can do coding");
    }
}

public class MultiLevel_Inheritance {
    public static void main(String[] args) {
        CollegeStudents cs = new CollegeStudents();
        cs.read();
        cs.write();
        cs.coding();
    }
}

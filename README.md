```java
import java.util.List;

public class Resume {
    // Profile
    public static final String PROFILE = "Aditya Kumar Singh";
    public static final String CONTACT = "Kolkata, India | adityakumarsingh.dev@gmail.com;

    // Experience
    public static final List<String> EXPERIENCE = List.of(
        "Accenture (Apr '24 - Present): Automated Salesforce migration, saving 75% time.",
        "EzeRx (Sep '23 - Mar '24): Mobile App Developer & Employee of the Month."
    );

    // Education
    public static final String EDUCATION = 
        "B.Tech in Computer Science & Engineering, Ramkrishna Mahato Govt. Engineering College (CGPA: 9.18)";

    // Skills
    public static final List<String> SKILLS = List.of(
        "C++", "Java", "Python", "Flutter", "Spring Boot", "Docker"
    );

    // Fun Fact
    public static final String FUN_FACT = "Good Things On the Way";

    // Optional: method to print resume info
    public static void printResume() {
        System.out.println("Profile: " + PROFILE);
        System.out.println("Contact: " + CONTACT);
        System.out.println("\nExperience:");
        EXPERIENCE.forEach(exp -> System.out.println("- " + exp));
        System.out.println("\nEducation:");
        System.out.println(EDUCATION);
        System.out.println("\nSkills:");
        SKILLS.forEach(skill -> System.out.print(skill + ", "));
        System.out.println("\n\nFun Fact: " + FUN_FACT);
    }

    public static void main(String[] args) {
        printResume();
    }
}

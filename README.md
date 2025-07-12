# Selenium-Java-TestNG

**A beginner-friendly UI test automation framework built using **Selenium WebDriver**, **Java**, and **TestNG** — designed and maintained by Krishna Mohan.**

## 🧰 Tech Stack

🟦 Java 
🧪 TestNG
🧭 Selenium WebDriver
📦 Maven
📄 Page Object Model (POM) design pattern


selenium-java-testng/
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── pages/               # Page Object Model classes (e.g., LoginPage.java)
│   │       └── utils/               # Utility classes (DriverManager, ConfigReader)
│   └── test/
│       └── java/
│           └── tests/              # TestNG test classes (e.g., LoginTest.java)
│
├── config/
│   └── config.properties           # Browser, URL, timeout, etc.
│
├── drivers/
│   └── chromedriver.exe           # (Optional) Store WebDriver binaries
│
├── testng.xml                     # TestNG suite file
├── pom.xml                        # Maven build file
├── .gitignore                     # Ignore target, .class, IDE files, etc.
├── README.md                      # Overview & usage
└── FRAMEWORK_BIO.md               # Detailed explanation of framework

# Scheduling App API (Java - In-Memory)

A minimal scheduling application written in Java (no frameworks, no databases) that allows you to:

- ✅ Create persons with name and unique email
- 📅 Schedule one-hour meetings (starting on the hour)
- 🔎 View a person's upcoming meetings
- 🔄 Suggest available meeting times for a group of people

---

## 🛠️ Tech Stack

- Java 17+
- Pure Object-Oriented Programming
- No Spring, No Database — everything is in-memory
- Modular design with services and models

---

## 🧩 Project Structure

com.scheduler
│
├── App.java # Console demo entry point
│
├── model/
│ ├── Person.java # Represents a user
│ └── Meeting.java # Represents a one-hour meeting
│
├── service/
│ ├── PersonService.java # Person creation & lookup
│ ├── MeetingService.java # Meeting creation & validation
│ └── ScheduleService.java # Schedule viewer & time slot suggester
│
└── store/
└── InMemoryStore.java # Simulates a simple repository


## 🚀 How to Run

### 1. Compile

javac com/scheduler/**/*.java

### 2. Run

java com.scheduler.SchedulerApp



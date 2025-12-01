<p align="center">
  <a href="https://craftcode.be/"><img src="./craftcode-full-color_RGB.png" alt="CraftCode Logo" width="320" /></a>
</p>

<h1 align="center">Java Versions Workshop @ CraftCode</h1>

<p align="center">
  Hands-on sessions exploring new Java releases — from “it compiled on Java 8” to “wow, this runs on Java 25”.
</p>

---

## 👋 Welcome

This GitHub organization hosts the material for **CraftCode’s Java Versions Workshops**.

Each repository here is a self-contained lab with:

- Starter code
- Unit tests that guide the exercises
- A ready-to-run cloud dev environment (via GitHub Codespaces)
- Notes on what changed between Java LTS versions and the latest release

If you’re here for a live session, you’re in the right place — everything you need for the workshop is inside this org.

---

## 🧑‍🏫 Who’s who

- **Instructor:** **John Wilkos**  
  Leads the sessions, walks through the new Java features, and answers all your “why did they change *that*?” questions.

- **Host & Support:** **Pieter Vercammen**  
  Keeps the tech running smoothly, helps troubleshoot setup issues, and, most importantly, **hands out cupcakes**.  
  (Yes, really. Come for Java 25, stay for the frosting.)

- **Company:** **CraftCode**  
  We care about clean code, modern tooling, and teaching in a way that’s practical, friendly, and slightly sugar-fueled.

---

## 🚀 How to use these repositories during a workshop

Most repositories in this org follow the same pattern:

1. **Accept the assignment / open the repo**  
   Your instructor (John) will share a link to the specific exercise repo.

2. **Open in GitHub Codespaces (recommended)**  
   - Click the green **“Code”** button.  
   - Choose **“Create codespace on main”**.  
   - A browser-based VS Code window will open with the correct **Java version (e.g. Java 25)** and tools preinstalled.

3. **Read the README in the repo**  
   Each workshop repo has:
   - A quick overview of the topic  
   - Steps to run tests  
   - Tasks you need to complete to “green” all tests

4. **Run the tests**  
   - You can use the **Testing** view in VS Code, or  
   - Use the terminal (for example):  
     ```bash
     ./mvnw test        # or mvn test / gradle test depending on the project
     ```

5. **Make the tests pass**  
   Your goal in each exercise is to implement or adapt the code so all tests pass under the *target Java version*.

---

## 🧩 What you’ll find here

Typical repositories in this org might include:

- **java-25-vs-last-lts** – Hands-on tour of what changed since the last LTS (language features, APIs, performance hints).
- **migration-exercises** – Small refactoring tasks that simulate upgrading a codebase from an older Java to a newer one.
- **tooling-and-builds** – Examples showing Maven/Gradle configuration for multi-version builds.

(Names may change over time, but the idea stays the same: small, focused labs.)

---

## ✅ What you need before a session

To keep things smooth and fast during a 2-hour workshop:

- A **GitHub account** (free) — already created and verified
- A **modern browser** (Chrome, Edge, Firefox, Safari)
- A **laptop + charger**
- Optional: a local JDK installed if you want to run things outside of Codespaces, but **not required**

If you hit any setup snags:
- In person: flag down **Pieter** (he’ll be the one near the cupcakes).  
- In the repo: open an **Issue** describing what’s going wrong.

---

## 🤝 Code of Conduct

We want these workshops to be friendly, inclusive, and fun.

- Be respectful and kind.
- Help others when you can.
- Ask questions — there are no “stupid” ones.
- Treat feedback as a way to get better, not as a judgment.

If something makes you uncomfortable, please let John or Pieter know.

---

## 💬 Feedback & Questions

Have ideas for future workshops or improvements?

- Open an **Issue** in the relevant repository.
- Or talk to us during/after the session — we genuinely want to make each workshop better than the last.

Thanks for learning with **CraftCode**  
… and may all your tests be green (and your cupcakes fresh).

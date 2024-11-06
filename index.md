# Index: Chirag's Cybersecurity Vault

## 🗂 Overview
- [Chirag's Cybersecurity Learning Journey](./Chirag%27s%20Cybersecurity%20Learning%20Journey.md): Introduction to my blog, covering my journey, goals, and the content I share.

## 🏷️ Sections

### 🔍 About the Blog
- [About the Blog](./About%20the%20Blog.md): Purpose of the blog, including learning goals, research areas, and key content types like research notes and CTFs.

### 📚 Literature Notes
- [Literature Notes](./Literature%20Notes.md): Notes on books, articles, and research papers I read, with key insights and takeaways that help shape my understanding of cybersecurity.

### 🔐 Topics Covered
- [Topics Covered](./Topics%20Covered.md): In-depth guides on command injection, packet processing, TLS mechanics, exploitation techniques, and filter evasion.

### ✍️ Learning Summaries
- [Learning Summaries](./Learning%20Summaries.md): Summarized insights from books, courses, and hands-on labs that have helped me in my journey.

### 🏁 CTF Challenges
- [CTF Challenges](./CTF%20Challenges.md): Notes and write-ups from Capture The Flag (CTF) challenges, linked to relevant learning areas.

### 🗓️ Weekly Write-Ups
- [Weekly Write-Ups](./Weekly%20Write-Ups.md): Day-by-day reflections on progress, challenges, and achievements.

### 🔬 Research Corner
- [Research Notes](./Research%20Notes.md): Deep dives into CVEs, offensive security techniques, protocols, and discoveries.

### 🚀 Project Updates
- [Project Updates](./Project%20Updates.md): Updates on ongoing projects that I am working on, with a focus on offensive security.

### 🛠️ My Projects
- [My Projects](./My%20Projects.md): Documentation of both personal and collaborative projects, including objectives, progress, and key outcomes.

## 🎯 My Learning Approach
- [My Approach](./My%20Approach.md): Detailed explanation of my hands-on practice, breaking down complexity, using networked knowledge, and reflections on learning.

## 🤝 Get Involved
- [Get Involved](./Get%20Involved.md): Information on how readers can connect, ask questions, and engage with my journey.

## 📜 License
- [License](./License.md): License details for sharing or adapting the content of the blog.

---

*Explore, learn, and join me on this cybersecurity journey!*

<!-- Dark Mode Toggle Button -->
<button id="dark-mode-toggle">Toggle Dark Mode</button>

<script>
// Toggle between light and dark mode
document.addEventListener("DOMContentLoaded", function() {
    const toggleButton = document.getElementById("dark-mode-toggle");
    toggleButton.addEventListener("click", function() {
        document.body.classList.toggle("light-mode");
        localStorage.setItem("theme", document.body.classList.contains("light-mode") ? "light" : "dark");
    });

    // Load saved theme from local storage
    if (localStorage.getItem("theme") === "light") {
        document.body.classList.add("light-mode");
    }
});
</script>

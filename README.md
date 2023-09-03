
<h1>Mr. Robot: 1 VM Penetration Testing Guide</h1>

<h2>Description:</h2>
<p>The Mr. Robot: 1 VM Penetration Testing Guide project is an in-depth, step-by-step walkthrough of the Mr. Robot: 1 virtual machine challenge available on VulnHub. This guide provides aspiring and experienced cybersecurity enthusiasts with a comprehensive roadmap to successfully conquer this capture the flag (CTF)-style challenge.</p>

<h2>Project Objectives:</h2>
<ol>
    <li><strong>Education and Skill Enhancement:</strong> This project aims to educate and enhance the penetration testing and ethical hacking skills of participants by taking them through the process of attacking a vulnerable virtual machine.</li>
    <li><strong>Real-world Simulation:</strong> It simulates real-world scenarios, offering users a practical and immersive experience in identifying and exploiting security vulnerabilities.</li>
    <li><strong>Learning Resources:</strong> The project serves as an educational resource, guiding users through reconnaissance, web application testing, exploitation, privilege escalation, and more.</li>
    <li><strong>Demonstrated Techniques:</strong> Participants will learn and apply various techniques, including web directory enumeration, brute-force attacks, reverse shell exploitation, privilege escalation, and more.</li>
</ol>

<h2>Contents:</h2>
<ul>
    <li><strong>Introduction:</strong> Provides an overview of the project's goals and the Mr. Robot: 1 VM.</li>
    <li><strong>Lab Setup:</strong> Describes the hardware and software environment used, including the setup of Kali Linux and the target VM.</li>
    <li><strong>Ground Rules:</strong> Outlines the rules and restrictions imposed for a realistic experience, emphasizing that the target VM is accessed solely from the attack platform (Kali Linux).</li>
    <li><strong>Reconnaissance:</strong> Covers the process of identifying the target's IP address, network information, and open ports. It also introduces the discovery of a website on the target.</li>
    <li><strong>Website Analysis:</strong> Details the analysis of the target's website, including its interactive features and the identification of the WordPress login page.</li>
    <li><strong>Web Directory Enumeration:</strong> Demonstrates the use of Nmap scripts to enumerate working sub-directories on the website, revealing that WordPress is in use.</li>
    <li><strong>Brute-force Attack:</strong> Explains the execution of a brute-force attack to obtain WordPress credentials, including username and password.</li>
    <li><strong>Reverse Shell:</strong> Describes the implementation of a reverse shell attack, enabling limited access to the target system.</li>
    <li><strong>Spawn a TTY Shell:</strong> Explains how to escape the limited shell, spawn a TTY shell, and elevate privileges to access user-specific files and keys.</li>
    <li><strong>Privileged Escalation:</strong> Guides users in the process of identifying and exploiting an executable with SUID permissions to gain root-level access to the target system.</li>
    <li><strong>Completion:</strong> Summarizes the successful completion of the challenge, including the acquisition of all three keys hidden within the VM.</li>
</ul>

<h2>Usage and Contribution:</h2>
<p>This project is a valuable resource for individuals interested in honing their cybersecurity skills through hands-on practice. Users are encouraged to follow the guide step by step to complete the Mr. Robot: 1 VM challenge independently. Contributions, such as additional tips, alternative approaches, and corrections, are welcomed through pull requests.</p>

<h2>Disclaimer:</h2>
<p>The information, techniques, and tools presented in this project are for educational purposes only. Users are advised to use these resources responsibly and ethically, adhering to all applicable laws and regulations. The project creator assumes no liability for misuse or any consequences resulting from unauthorized activities.</p>

<p>By following this guide, participants can embark on a journey to sharpen their penetration testing skills, emulate real-world scenarios, and conquer the Mr. Robot: 1 VM challenge.</p>

<p><i>Ayush Sharma & Aditya Lawand</i></p>

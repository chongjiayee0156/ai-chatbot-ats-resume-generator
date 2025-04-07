<p align="center">
  <img src="ats-generator.jpeg" alt="Logo" width="200" />
</p>

# Coze AI Chatbot for ATS-Friendly Resume Generation



<p align="center">
  <img src="https://github.com/user-attachments/assets/8f0e10b9-7fe2-4f5e-9da4-a42bde5a7a9b" alt="Coze AI Chatbot Demo" width="800" />
</p>

## Demo 🎬

### Demo Videos:

-  [![manual-prompt](https://img.shields.io/badge/Manual%20Prompt-Watch%20Video-red?style=for-the-badge)](https://youtu.be/3-9s5kqQRYQ?si=WTaqPAAybSa6-U-u) 
-  [![resume-refinement](https://img.shields.io/badge/Resume%20Refinement-Watch%20Video-red?style=for-the-badge)](https://youtu.be/gwf3PMt0sVY?si=DfYucVImqQ1jt2AZ) 
-  [![linkedin-import](https://img.shields.io/badge/LinkedIn%20Import-VWatch%20Video-red?style=for-the-badge)](https://youtu.be/_zysCtnA6aM?si=izBe0BNdR8uv2h9n) 


## Project Overview 🌟

- Built on the **Coze AI** platform, `ats-generator` is developed using the **low-code/no-code (LCNC)** approach
- Aim to generate resumes that are **ATS-friendly** and dynamically tailored to the needs of users.
- Checkout report for more ino.

## Features 🚀

- **📝 Manual Data Entry:** Users can input their resume information freely without being restricted to predefined sections.
- **🔧 Resume Refinement:** Users can upload existing resumes in PDF format to improve formatting, structure, and content.
- **🔗 LinkedIn Integration:** Seamlessly import user profile data from LinkedIn for a faster and more personalized resume creation experience.
- **⚙️ ATS-Friendly Formatting:** Ensures all resumes are optimized for Applicant Tracking Systems (ATS), improving chances of passing automated screenings.
- **📥 Downloadable DOCX Output:** Generated resumes are available in DOCX format, allowing for easy editing and customization.



## Solution Architecture 🏗️

The architecture of Coze AI Chatbot is designed to provide a seamless, intuitive user experience, involving the following key components:

- **Main Workflow:** Accepts user input (in JSON format) and processes it to generate a downloadable DOCX resume file.
- **Plugins:**
  - **🖨️ Resume Generator:** Converts structured JSON data into a professional DOCX resume using Python (hosted on Render).
  - **📄 Resume Reader:** Extracts data from uploaded resumes (PDF) for content refinement.
  - **🔒 LinkedIn Authorizer:** Imports data from LinkedIn profiles to create resumes, with some limitations based on LinkedIn’s free API access.
- **Cloud Storage & API Integration:** Resumes are stored in **Supabase**, where users can download their DOCX files.

![Architecture Diagram](architecture.png)

## Technologies Used 🛠️

- **💡 Coze AI:** Low-code/no-code platform powering the chatbot interface.
- **🐍 Python & Flask:** Backend stack used to process resume data and generate DOCX files.
- **📄 python-docx:** Python library used to create and format DOCX files.
- **☁️ Render:** Hosting platform for API services that power the resume generation process.
- **📦 Supabase:** Cloud database and storage solution for managing and serving generated DOCX resumes.

## Future Enhancements 🔮

- **🔗 Expanded LinkedIn API Access:** Enabling richer data extraction from LinkedIn profiles for more comprehensive resume generation.
- **⚙️ Improved Resume Parsing & Formatting:** Enhancing AI capabilities to parse and format resumes with greater accuracy and efficiency.
- **💼 Industry-Specific Templates:** Adding specialized resume templates tailored for different professions and industries.
- **🧑‍💻 Job-Matching Integration:** Enabling users to find job opportunities that match their resume profiles, creating a more seamless job search experience.

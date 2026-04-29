========================================
  ASSETS FOLDER — Shashwat Bhadre Portfolio
========================================

FOLDER STRUCTURE:
-----------------
assets/
├── photos/
│   ├── profile.jpg          ← Your main profile photo (used in Hero section)
│   ├── campus.jpg           ← Campus life photo
│   ├── team-event.jpg       ← Team/event photo
│   └── achievement.jpg      ← Achievement/award photo
│
├── certificates/
│   ├── coursera.jpg         ← Coursera certificate (scanned/screenshot)
│   ├── netcad.jpg           ← NetCAD certificate
│   ├── yuva-ai.jpg          ← Yuva AI certificate
│   ├── ai4a.jpg             ← Ai4A project certificate/photo
│   ├── design-thinking.jpg  ← Design Thinking certificate/photo
│   └── ace-project.jpg      ← ACE project certificate/photo
│
└── projects/
    ├── ai4a-screenshot.jpg          ← Screenshot of Ai4A project
    ├── design-thinking-screenshot.jpg ← Screenshot of Design Thinking project
    ├── ace-screenshot.jpg           ← Screenshot of ACE project
    └── portfolio-screenshot.jpg     ← Screenshot of this portfolio

HOW TO REPLACE IMAGES IN THE WEBSITE:
--------------------------------------
After placing your images in the correct folders,
update index.html as follows:

1. PROFILE PHOTO (Hero section):
   Find: <div class="avatar-placeholder"><i class="fas fa-user"></i></div>
   Replace with: <img src="assets/photos/profile.jpg" alt="Shashwat Bhadre" style="width:100%;height:100%;object-fit:cover;"/>

2. GALLERY IMAGES:
   Find each: <div class="gal-placeholder ...">
   Replace with: <img src="assets/certificates/coursera.jpg" alt="Coursera Certificate"/>

3. PROJECT SCREENSHOTS:
   Find each: <div class="project-placeholder">
   Replace with: <img src="assets/projects/ai4a-screenshot.jpg" alt="Ai4A Project"/>

TIPS:
-----
- Use JPG or PNG format
- Recommended size: 800x600px or larger for certificates
- Profile photo: square crop works best (e.g. 500x500px)
- Keep file sizes under 500KB each for fast loading

========================================

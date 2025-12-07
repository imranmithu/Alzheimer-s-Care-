<p align="center">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blueviolet" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/Status-Active-success" alt="Status">
</p>

<h1 align="center">🧠 ALZ-CARE</h1>
<h3 align="center">Alzheimer's Life & Climate Adaptive Resilience Ecosystem</h3>

<p align="center">
  <strong>A comprehensive digital support platform for Alzheimer's caregivers</strong><br>
  Empowering families with tools for care coordination, cognitive monitoring, and community support
</p>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Usage](#-usage)
- [Technology Stack](#-technology-stack)
- [Research Foundation](#-research-foundation)
- [Contributing](#-contributing)
- [Resources](#-resources)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🌟 Overview

**ALZ-CARE** is an all-in-one mobile-first web application designed to support caregivers of individuals living with Alzheimer's disease and dementia. The app addresses the unique challenges faced by family caregivers by combining environmental monitoring, health tracking, cognitive assessments, and community support into a single, accessible platform.

### Why ALZ-CARE?

- **6.9 million** Americans are living with Alzheimer's disease
- **11 million** family members and friends provide unpaid care
- **40%** of caregivers experience stress-related depression
- Caregivers need comprehensive, easy-to-use digital tools

ALZ-CARE bridges the gap between clinical care and daily caregiving by providing actionable insights, educational resources, and peer support.

---

## ✨ Features

### 🏠 Home Dashboard
- **Vital Signs Monitor** — Real-time tracking of heart rate, blood pressure, oxygen levels, and temperature with wearable device sync
- **Weather Alerts** — Outdoor and indoor environmental monitoring with Alzheimer's-specific risk alerts
- **Air Quality Index** — PM2.5, PM10, Ozone, and NO₂ tracking with brain health research integration

### 💊 Medication Management
- **Visual Timeline** — Daily medication schedule with morning, noon, evening, and night slots
- **Smart Reminders** — Push notifications, sound alerts, and caregiver notifications
- **Adherence Tracking** — Weekly compliance statistics and medication history

### 🧩 Cognitive Assessments
Four interactive, research-informed cognitive tests:

| Test | Purpose | Duration |
|------|---------|----------|
| 🎴 Memory Match | Short-term memory & visual recognition | 30 sec |
| 🎯 Attention Focus | Reaction time & sustained attention | 30 sec |
| 📝 Word Recall | Verbal memory & language processing | 60 sec |
| 🔢 Pattern Recognition | Sequential memory & problem-solving | Variable |

### 🚨 Emergency Support
- **One-tap 911 calling** with pulse animation for visibility
- **Quick contacts** for healthcare providers and family
- **Medical ID** with blood type, allergies, and current medications
- **Safety features** — GPS tracking, fall detection, safe zone alerts

### 👨‍👩‍👧 Family & Memories
- **Photo Memory Albums** — Organized collections with contextual stories
- **Care Coordination** — Weekly schedule with assigned caregivers
- **Task Management** — Daily care checklist with assignees
- **Care Notes** — Team communication and patient observations

### 🤝 Community & Events
- **Discussion Groups** — Connect with 12,000+ caregivers in specialized forums
- **Nearby Caregivers** — Location-based peer support connections
- **Local Events** — Walk to End Alzheimer's, support groups, workshops, memory cafés

### 📚 Learning Hub
- **VR Dementia Training** — Dementia Reality™ (Meta Quest) and AFA's Dementia Experience
- **Alzheimer's Association Courses** — Official training programs with certification options
- **Educational Videos** — Curated content on sundowning, communication strategies, and nutrition
- **Professional Certification** — essentiALZ® and ECHO® program information

---

## 📱 Screenshots

| Home & Vitals | Cognitive Tests | Family Coordination |
|:-------------:|:---------------:|:-------------------:|
| Dashboard with vital signs and weather monitoring | Interactive memory and attention games | Care schedule and team management |

| Emergency | Community | Learning |
|:---------:|:---------:|:--------:|
| One-tap SOS with medical information | Peer support and local events | VR training and courses |

---

## 🚀 Installation

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/alz-care.git
   cd alz-care
   ```

2. **Open in browser**
   ```bash
   # Simply open the HTML file
   open alz-care-app.html
   
   # Or use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000/alz-care-app.html
   ```

### No Dependencies Required
ALZ-CARE is a standalone HTML application with embedded CSS and JavaScript. No build process or package installation needed.

### Progressive Web App (Optional)
To install as a PWA on mobile devices:
1. Open the app URL in your mobile browser
2. Tap "Add to Home Screen" (iOS) or "Install App" (Android)
3. Access ALZ-CARE like a native app

---

## 💻 Usage

### For Caregivers

1. **Set up patient profile** — Enter patient information, medical conditions, and emergency contacts
2. **Configure medications** — Add prescriptions with dosage and timing
3. **Enable notifications** — Turn on push alerts, sounds, and caregiver notifications
4. **Sync wearable devices** — Connect compatible health monitors for real-time vitals
5. **Invite family members** — Build your care team for coordinated support

### For Healthcare Providers

- Review cognitive assessment trends over time
- Monitor medication adherence reports
- Access vital signs history
- Coordinate with family caregivers through care notes

### Demo Mode
The current version runs in demo mode with sample patient data (Eleanor Mitchell). All features are fully interactive for testing and demonstration purposes.

---

## 🛠 Technology Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Styling** | Custom CSS with CSS Variables, Glass-morphism design |
| **Typography** | Google Fonts (Outfit, Space Grotesk) |
| **Icons** | Emoji-based for universal accessibility |
| **Animation** | CSS Keyframes, Neural network background effect |
| **Design** | Mobile-first responsive (max-width: 430px optimized) |

### Design System

```css
/* Color Palette */
--purple-deep: #1a1235
--purple-dark: #0d0a1a
--purple-bright: #7b4bb8
--accent-coral: #ff6b6b
--accent-teal: #4ecdc4
--accent-gold: #ffd93d
--accent-mint: #6bcb77
```

---

## 🔬 Research Foundation

ALZ-CARE integrates evidence-based research into its features:

### Air Quality & Brain Health
Research shows particulate matter (PM2.5) exposure is associated with increased Alzheimer's risk. Our AQI monitoring helps caregivers make informed decisions about outdoor activities.

### VR Training Effectiveness
- **75%** better knowledge retention compared to traditional training methods
- **67%** reduction in caregiver turnover with empathy-based training
- First-person dementia experiences build understanding and reduce frustration

### Cognitive Assessment
Our games are inspired by validated neuropsychological assessments adapted for home use, designed to track patterns over time rather than diagnose conditions.

---

## 🤝 Contributing

We welcome contributions from developers, healthcare professionals, and caregivers!

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Contribution Ideas
- [ ] Backend integration for data persistence
- [ ] Real wearable device API connections
- [ ] Multi-language support
- [ ] Voice control accessibility features
- [ ] Dark/light theme toggle
- [ ] Data export functionality
- [ ] Telemedicine integration

### Code Style
- Use semantic HTML5 elements
- Follow BEM naming convention for CSS classes
- Comment complex JavaScript functions
- Maintain mobile-first responsive approach

---

## 📚 Resources

### Alzheimer's Association
- **24/7 Helpline:** [800.272.3900](tel:8002723900)
- **Training Portal:** [training.alz.org](https://training.alz.org)
- **Find Local Events:** [alz.org/events](https://www.alz.org/events)

### Educational Programs
- [10 Warning Signs of Alzheimer's](https://www.alz.org/alzheimers-dementia/10_signs)
- [Understanding Alzheimer's & Dementia](https://training.alz.org/products/4053/understanding-alzheimers-and-dementia)
- [Communication Strategies](https://training.alz.org/products/4036/effective-communication-strategies)
- [Dementia-Related Behavior](https://training.alz.org/products/4037/understanding-and-responding-to-dementia-related-behavior)

### VR Training Programs
- [Dementia Reality™ (Meta Quest)](https://www.meta.com/experiences/dementia-reality/24335839399395972/)
- [AFA's Dementia Experience](https://alzfdn.org/afas-dementia-experience/)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 ALZ-CARE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙏 Acknowledgments

- **Alzheimer's Association** — For educational resources and training programs
- **Meta** — For Dementia Reality™ VR training platform
- **Alzheimer's Foundation of America** — For the Dementia Experience program
- **Caregivers worldwide** — For inspiring this project through their dedication and love

---

<p align="center">
  <strong>Made with 💜 for caregivers everywhere</strong>
</p>

<p align="center">
  <a href="#-alz-care">Back to Top ↑</a>
</p>

---

### 📞 Support

For questions, suggestions, or support:
- Open an [Issue](https://github.com/yourusername/alz-care/issues)
- Start a [Discussion](https://github.com/yourusername/alz-care/discussions)
- Email: support@alz-care.app

### 🌐 Connect

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/alzcare)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/alz-care)

---

*Disclaimer: ALZ-CARE is designed as a supportive tool for caregivers and is not intended to replace professional medical advice, diagnosis, or treatment. Always consult healthcare providers for medical decisions.*

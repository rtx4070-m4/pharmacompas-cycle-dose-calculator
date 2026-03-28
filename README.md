💊 PharmaCompas — Cycle Designer & Dose Calculator
<p align="center">

Educational pharmacology toolkit for cycle planning, PCT estimation, and weight-based drug dosing.

</p> <p align="center">










</p>
📖 Overview

PharmaCompas is a standalone web-based pharmacology calculator designed for educational exploration of drug dosing models and anabolic cycle planning concepts.

The application includes two major modules:

1️⃣ Cycle Designer + PCT Assistant
2️⃣ Weight-Based Drug Dose Calculator

It is implemented as a single-file web application and runs entirely inside the browser without requiring installation or internet access.

The project demonstrates how basic pharmacokinetic reasoning and dosing models can be implemented in an interactive tool.

The application interface and logic are contained in a single HTML file.

⚠️ Important Disclaimer

This tool is for educational and informational purposes only.

It does not provide medical advice and must not be used for clinical decision making or drug use planning.

Misuse of anabolic steroids or other drugs may cause serious health risks.
Always consult a qualified medical professional.

✨ Key Features
🏋️ Cycle Designer

Create a multi-compound cycle with:

compound selection
weekly dosage input
cycle duration
automatic totals

The system calculates:

total weekly dosage
total cycle load
longest compound duration
🧪 PCT Recommendation Engine

Generates a post-cycle therapy protocol suggestion based on cycle severity:

Mild cycles
Moderate cycles
Heavy cycles

Includes:

Clomiphene protocol
Tamoxifen protocol
HCG recommendations
ester-dependent timing guidance
⚠️ 19-Nor Compound Detection

The tool detects compounds associated with prolactin-related side effects, including:

Trenbolone
Nandrolone
Deca-Durabolin
NPP

It provides warnings and prolactin management notes.

💊 Drug Dose Calculator

Weight-based dosing calculator using mg/kg pharmacological models.

Inputs:

Body weight
Dose per kg
Frequency per day
Treatment duration

Outputs:

single dose
daily dose
total treatment dose
🧮 Calculation Logic
Weight-Based Dose
Single Dose (mg) = Body Weight (kg) × Dose per kg
Daily Dose (mg/day) = Single Dose × Frequency
Total Course Dose (mg) = Daily Dose × Duration (days)
Cycle Load
Total Weekly Dose = Sum of all compound weekly doses
Total Cycle Dose = Weekly Dose × Duration (weeks)
Cycle Severity Classification
Level	Criteria
Mild	< 300 mg/week
Moderate	300–600 mg/week
Heavy	> 600 mg/week

Used to generate PCT protocol recommendations.

🧩 Application Modules
1️⃣ Cycle Designer + PCT

Allows users to:

add multiple compounds
set weekly dosage
define duration
compute cycle totals
generate PCT recommendations
2️⃣ Drug Dose Calculator

Supports weight-based pharmacology calculations:

mg/kg dosing
dosing frequency
treatment duration
total drug requirement
🖥️ User Interface

The application uses a tab-based interface:

🏋️ Cycle Designer + PCT
💊 Drug Dose Calculator

Key UI components:

compound rows
interactive form inputs
responsive layout
dynamic calculation updates
🏗️ Project Architecture
pharmacompas
│
├── index.html
│
└── README.md

The entire application includes:

Component	Purpose
HTML	interface structure
CSS	UI styling
JavaScript	calculation logic

All functionality is implemented inside one standalone HTML file.

🚀 Getting Started
Run Locally

Clone the repository:

git clone https://github.com/yourusername/pharmacompas.git

Open the application:

index.html

in any modern browser.

No installation required.

📱 Browser Compatibility

Supported browsers:

Chrome
Firefox
Edge
Safari

Mobile devices are also supported due to responsive layout design.

📸 Screenshots

Recommended screenshot sections:

screenshots/
├── cycle-designer.png
├── pct-generator.png
├── drug-dose-calculator.png
🎯 Educational Applications

PharmaCompas can be used for:

pharmacology learning
drug dosing practice
pharmacokinetics teaching
pharmacy student demonstrations
research prototypes
⚙️ Technologies Used
Technology	Role
HTML5	Application structure
CSS3	Responsive UI
JavaScript	Calculation engine
Browser APIs	Client-side execution
🌱 Future Improvements

Possible upgrades:

pharmacokinetic half-life models
blood concentration simulation
ester decay modeling
cycle timeline visualization
interactive PCT planner
CSV export
mobile PWA support
🤝 Contributing

Contributions are welcome.

Steps:

Fork the repository
Create a feature branch
Add improvements
Submit a Pull Request
📜 License

Released under the MIT License.

You may use, modify, and distribute this project for educational and research purposes.

⭐ Support

If you find this project useful:

⭐ Star the repository
🍴 Fork the project
📢 Share with students and researchers

💡 Project Goal

To demonstrate how pharmacological dosing logic and cycle modeling can be implemented in a lightweight educational web application.

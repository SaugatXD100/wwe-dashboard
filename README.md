# wwe-dashboard
 WWE Titles Dashboard

A web-based dashboard that displays WWE title statistics for superstars across all brands — RAW, SmackDown, NXT, and Unbranded superstars.  
The data loads automatically from CSV files and supports search, brand filtering, multi-state sorting, and champion highlighting.

⭐ Features

✅ 1. Live Data Loading
- Reads wwe_titles_combined.csv and current_champions.csv directly in the browser using PapaParse.
- Automatically removes empty rows.

🔍 2. Search Bar
- Search any superstar instantly.
- Works together with brand filters and sorting.

🟥🟦🟨 3. Brand Filtering
Filter superstars by:
- RAW  
- SmackDown  
- NXT  
- Unbranded  

Brand colors applied automatically.

↕️ 4. Sorting System (3-State Mode)
Click any column to cycle sorting:
1. Ascending
2. Descending
3. Reset to original order

🏆 5. Current Champion Glow
- Superstars listed in current_champions.csv get a golden glow.
- Update the CSV anytime to reflect new champions — no need to edit the HTML.

📁 File Structure

/
├── index.html  
├── wwe_titles_combined.csv  
├── current_champions.csv  
├── README.md  
└── LICENSE  

🚀 How to Run

Method 1 — VS Code Live Server
1. Install the "Live Server" extension  
2. Right-click index.html → Open with Live Server  

Method 2 — GitHub Pages
1. Push your project to a GitHub repository  
2. Go to Settings → Pages  
3. Select "Deploy from a branch"  
4. Branch: main → folder: /(root)  
5. Save  

Your site will be live at:  
https://wwedashboard.xyz/

📝 Updating Champions
To change who glows as a champion:
1. Open current_champions.csv  
2. Edit the wrestler names  
3. Commit/upload the file  

The website updates automatically.

🛠 Technologies Used

- HTML  
- CSS  
- JavaScript  
- PapaParse (CSV parsing)  
- GitHub Pages (hosting)  

## 📜 License

This project is licensed under the **MIT License** — meaning you can use, modify, and publish it freely.

🤝 Contributing

Pull requests are welcome.  
Feel free to submit improvements or new feature ideas.

📧 Contact

If you want more features or need help, feel free to open an issue.

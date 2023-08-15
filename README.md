# Keno-DataVis
A program that gets data from Keno using an API for the purpose of displaying and interacting with the data. For now the program is in it's early stages, only a basic command line interface for now but there is alot planned. 

### Setup 
**NOTE: WHEN SWITCHING BETWEEN DEV VERSIONS IT IS BEST TO DROP/DELETE THE MONGODB DATABASE**

0. Download all files in the ActiveDev Branch/Latest Release
1. Go to the [Keno-API pypi page](https://pypi.org/project/kenoAPI/) and follow instructions to download the package.
2. You also need the following packages, [Certifi](https://pypi.org/project/certifi/) and [Pymongo](https://pypi.org/project/pymongo/)
3. Follow this [Database Setup Guide](https://gist.github.com/CatotronExists/2776b4175cb21c23d10f16a62a3f68f0)
4. Run Setup.py, if any errors occur repeat step 3 then open an issue with the 'help' label.

### Credits
API Created by "JGolafshan" - Joshua Golafshan [API](https://github.com/JGolafshan/keno-api)

Win Data sourced from [Keno Game Guide](https://www.keno.com.au/keno-pdfs/VIC_Game%20Guide.pdf)\
*Data is sourced from the Victorian version, win amounts are the same across all states (as of now). If any win data is wrong, open an issue!*

### Check List
- [x] Gets data and Displays in easy to read format
- [x] Simulate betting (using a virtual money system, choose numbers and see how much you would win)
  - [x] Compatible with Custom Numbers and "Kwikpik"
- [x] Ability to input your bet and display results in real time
  - [x] Displays total winnings (per game and total)
  - [x] Compatible with different modes (Mega Millions, Classic, T/H)
- [x] Saves Data to a database
- [ ] Web page to display data though the use of an API from that database
- [ ] Full Breakdown of data
- [ ] Predict most likely to win numbers using trends?

### Roadmap to v1.0
- [ ] v1.0 | Completion (xx/xx/2023)\
- [ ] v0.9 | Browsing Data (xx/xx/2023)\
- [ ] v0.8 | Trends and Graphs (xx/xx/2023)\
- [ ] v0.7 | Data Visualised (xx/xx/2023)\
- [ ] v0.6 | User Input Returns (xx/xx/2023)\
- [ ] v0.5 | Migration to Python Backend, Html Frontend (xx/xx/2023)\
- [x] v0.4 | Database Connection (15/08/2023)\
- [x] v0.3 | Bet Simulation (25/07/2023)\
- [x] v0.2 | Bet Monitoring (22/07/2023)\
- [x] v0.1 | First Stable Release (21/06/2023)

### Disclaimer
This program is being made for educational purposes only, use at your own risk.
If you wish to use this program you have to download and run it on your machine, there will be no public database. You have to collect it, which can be done with this program.
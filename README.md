![header](https://capsule-render.vercel.app/api?type=Cylinder&color=003580&text=Booqueen.com&height=180&fontSize=50&fontColor=fff)
## ✨ Booqueen.com
- A web development project benchmarking **booking.com**, an online lodging reservation platform.
- Project Period : 2022. 03. 02 ~ 2022. 04. 08
- Team Size : 5 members
- Project Summary<br>
  ✔ User : Provides a convenient service to search and book hotels.<br>
  ✔ Partner (Hotel Manager) : Provides management services including hotel policies, rooms, and revenue management.<br>
  ✔ Admin (Site Administrator) : Provides full platform management, including statistics, payouts, and overall site monitoring.

<img width="2986" height="1408" alt="Gemini_Generated_Image_ykz461ykz461ykz4" src="https://github.com/user-attachments/assets/fb09b1f5-a59c-4438-82d3-3e15ecd58635" />

<br><br>
<div align="center">🛠<b> Tech Stack </b>🛠</div><br>
<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/>
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white"/>
  <img src="https://img.shields.io/badge/JSON-000000?style=flat&logo=JSON&logoColor=white"/><br>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=Bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=flat&logo=Eclipse IDE&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat&logo=Apache Tomcat&logoColor=black"/>
  <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat&logo=Amazon S3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat&logo=Amazon AWS&logoColor=white"/><br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=PostgreSQL&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>
</div><br>

# 1. Motivation
While brainstorming project topics with the team, we found the challenge of implementing diverse and complex features—such as date pickers, multi-layered filters, and interactive maps—highly compelling. This inspired us to build a full-scale reservation platform.
<br><br>

# 2. Development Environment
| Category | Specifications |
| :------------: | :-------------: |
| OS | Windows 10 64bit |
| Languages | Java, SQL, HTML, Javascript, CSS, JQuery, Ajax, XML, JSON |
| Dev Tools | Eclipse, PgAdmin, Maven, Java ORM Plugin |
| Frameworks | Spring Framework 5.3.4, MyBatis, Bootstrap |
| Database | PostgreSQL 12.9 |
| WAS | Apache Tomcat 9.0 |
| Web Browser | Chrome |
| VCS | Git, Github |
| Libraries | JSTL, lombok, aspectj, servlet-api, jackson, poi, amazonaws, commons-fileupload |
| Open Source / APIs | Kakao Map API, Kakao Login API, IamPort API |

<br><br>

# 3. Key Features

### 💛 User Features

- Sign-up, Standard Login, Kakao Social Login, Profile Editing, Logout
- Search for hotels by destination and travel dates from the main page
- Filter hotel search results using detailed criteria on the results page
- Sort hotel listings by reviews, price, or ratings
- View available hotels and nearby tourist attractions on a map using the Kakao Map API
- Dynamically update the hotel list based on the new center coordinates when moving the map
- Re-search dates, view hotel location/facilities/policies/reviews/Q&A/room photos, distance to attractions, and add/remove from Wishlist on the hotel details page
- Provide alternative available dates and pricing information if there are no rooms available on the selected dates
- Secure hotel booking, payment processing, and confirmation receipt printing using the Iamport API
- Live 1:1 chat between users with active bookings and hotel partners
- Post hotel reviews after completing a stay
- Cancel unfulfilled hotel reservations and print cancellation receipts
- Account deletion (disabled if there are active, unfulfilled hotel reservations)

### 💚 Partner (Hotel Manager) Features

- Sign-up, Hotel Registration, Password Change, Logout
- Add new rooms, view room availability via a calendar dashboard, register bookable rooms, and update daily room statuses
- View full booking lists, search booking details, access deep-dive reservation pages, and monitor user reviews
- Manage booking life cycles (Before Stay / Checked In / Completed / Request Payout from Site Administrator)
- Report fraudulent or problematic guests
- Manage hotel photos, operational policies, and room details
- Manage customer inquiries and live 1:1 chat with guests
- Download billing/invoice lists as Excel files
- Access data analytics dashboards (Current Month Revenue, Average Daily Rate [ADR], and Monthly Revenue Trends)

### 💙 Site Administrator (Admin) Features

- Login, Logout
- View and inspect profiles/details of regular users, partners, and registered hotels
- Manage reported users
- Suspend and block malicious partner accounts
- Manage customer service boards, featured travel destinations (main banners), and Terms of Service
- Track live booking metrics and audit full transaction histories
- Manage partner payout requests

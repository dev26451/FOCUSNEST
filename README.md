# FOCUSNEST
FocusNest là một nền tảng phòng học ảo dành cho học sinh, sinh viên, đặc biệt hướng tới học sinh Việt Nam ôn thi THPTQG.

Thay vì chỉ là một ứng dụng Pomodoro, FocusNest kết hợp Focus Timer + Study Room + Todo + Gamification + Learning Tools + Statistics + Social Features trong một không gian học tập duy nhất.

✨ Features
⏱ Focus & Productivity
Pomodoro Timer với nhiều preset và chế độ tùy chỉnh
Free Timer / Countdown
Theo dõi thời gian học theo môn và chủ đề
Heartbeat & session tracking
Focus Score
Todo list với priority, deadline và subtasks
Daily / Weekly statistics
Study streak
👥 Virtual Study Rooms
Phòng học realtime
Public & private rooms
Hiển thị thành viên đang học
Presence / study status
Room themes
Realtime interactions
Leaderboard theo ngày, tuần, tháng và season
🎮 Gamification
XP & Coins
Rank system
Daily / Weekly / Seasonal Quests
Achievements
Shop & Inventory
Battle Pass
Focus Duel
Ghost Race
World Boss
Seasonal progression
🏝️ Study Island

Mỗi người dùng có một Study Island riêng.

Thời gian học có thể giúp xây dựng và nâng cấp các công trình theo từng môn học, mở khóa decoration và ghé thăm island của bạn bè.

📚 Learning Tools
Subject Roadmap / Skill Tree
Flashcards
Spaced-repetition workflow
Mistake Notebook
Quiz Arena
Mock Exams
Q&A Community
🤖 AI & Analytics
AI Coach Nesty
Socratic-style guidance
Focus DNA
Weekly Study Wrapped
Daily briefing
Personalized study insights
Mood check-in & wellbeing tools

AI integration hiện tại có thể sử dụng simulated responses và có thể được kết nối với AI provider thật trong các phiên bản tiếp theo.

🤝 Social
Friends
Teams
Team study goals
Study Buddy
Island visits
Community Q&A
🏫 Extensions
Class management
Teacher invite codes
Parent reports với consent
Moderation / Admin tools
Reports & moderation history
🛠️ Tech Stack

Frontend

Next.js
React
TypeScript
Tailwind CSS
shadcn/ui

Backend

Supabase
PostgreSQL
Supabase Auth
Supabase Realtime
Supabase Storage

Testing

Vitest
Playwright

Architecture

Turborepo monorepo
Domain-based modules
TypeScript strict mode
Mobile-first responsive design
🗺️ Project Structure
FocusNest/
├── apps/
│   ├── web/
│   │   ├── app/
│   │   ├── components/
│   │   ├── features/
│   │   ├── lib/
│   │   └── ...
│   │
│   └── ...
│
├── packages/
│   ├── ui/
│   ├── config/
│   ├── types/
│   └── ...
│
├── supabase/
│   ├── migrations/
│   ├── seed/
│   └── ...
│
├── tests/
├── docs/
├── .env.example
├── package.json
└── README.md
🚀 Getting Started
1. Clone repository
git clone https://github.com/your-username/focusnest.git
cd focusnest
2. Install dependencies
npm install
3. Configure environment variables

Copy:

cp .env.example .env.local

Sau đó cấu hình các biến môi trường cần thiết cho Supabase và authentication.

4. Setup Supabase
Tạo một project Supabase
Chạy các migration trong thư mục supabase/migrations
Seed dữ liệu nếu cần
Cấu hình Google OAuth trong Supabase Auth
5. Run development server
npm run dev

Mở:

http://localhost:3000
🔐 Privacy & Safety

FocusNest được thiết kế với đối tượng học sinh, bao gồm cả người dùng dưới 18 tuổi, nên privacy và safety là một phần quan trọng của hệ thống.

Một số nguyên tắc:

Camera và microphone mặc định tắt
Không ghi hoặc lưu hình ảnh từ camera
RLS cho dữ liệu người dùng
Private profile
Không công khai email hoặc thông tin cá nhân nhạy cảm
Report / Block users
Moderation tools
Server-side validation
Rate limiting
Account & data deletion
Session / XP anti-abuse mechanisms
📊 Database

FocusNest sử dụng PostgreSQL thông qua Supabase với hệ thống dữ liệu cho:

Users & Profiles
Study Sessions
Todos
Rooms & Members
XP / Ranks / Seasons
Leaderboards
Quests
Achievements
Shop & Inventory
Friends
Teams
Study Islands
Flashcards
Mistakes
Quizzes
Mock Exams
Q&A
Notifications
Events
Moderation
Classes
Parents
Battle Pass
...

Database được tổ chức với:

RLS Policies
Foreign Keys
Indexes
Database Triggers
Seed Data
🎨 Design

FocusNest theo đuổi phong cách:

Cute · Warm · Calm · Focused

Pastel-inspired design
Soft rounded components
Dark mode
Mobile-first
Vietnamese-first UI
Lightweight animations
Consistent iconography

Mục tiêu là tạo cảm giác giống một “căn phòng học kỹ thuật số” thay vì một dashboard khô khan.

🗺️ Roadmap
✅ Completed
Foundation & Authentication
Personal Study Desk
Pomodoro & Tracking
Virtual Study Rooms
Leaderboards
Gamification
Study Island
Teams & Social
Learning Tools
AI Coach & Analytics
Classes & Parent features
Battle Pass
Moderation tools
🔮 Future
Real AI provider integration
Advanced Study Island graphics
Chrome extension
Whiteboard
Full internationalization
More learning analytics
Additional integrations
🤝 Contributing

Contributions, ideas and bug reports are welcome.

Before opening a pull request, please make sure:

npm run lint
npm run test

and, when applicable:

npm run build
📄 License

This project is currently under development.

License details will be added in a future release.

💡 Vision

FocusNest hướng tới việc trở thành một Personal Study OS cho học sinh và sinh viên:

Goal
  ↓
Plan
  ↓
Focus
  ↓
Study Together
  ↓
Learn
  ↓
Track Progress
  ↓
Improve

Don't just spend more time studying.
Build a better way to study.

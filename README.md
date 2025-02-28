# Synthetic Company Data Generator

This project allows users to populate databases with synthetic data that represents company data. The user can specify most parameters associated with this data and can then use the syntheised database to model and test programs associated with business needs. 

## Database structure in firebase: 

📂 firestore-root
 ├── 📂 users
 │   ├── 📄 user_123
 │   ├── 📄 user_456
 │   ├── 📄 user_789
 │   └── ...
 │
 ├── 📂 teams
 │   ├── 📄 team_abc
 │   ├── 📄 team_def
 │   ├── ...
 │
 ├── 📂 calendar
 │   ├── 📄 user_123
 │   │    ├── events (Array of meetings)
 │   ├── 📄 user_456
 │   │    ├── events (Array of meetings)
 │
 ├── 📂 offices
 │   ├── 📂 office_1
 │   │   ├── 📂 rooms
 │   │   │   ├── 📄 room_101
 │   │   │   │    ├── busySlots (Array of scheduled meetings)
 │   │   │   ├── 📄 room_102
 │   │   │   ├── 📄 room_103
 │   │   │   ├── ...
 │   ├── 📂 office_2
 │   │   ├── 📂 rooms
 │   │   │   ├── 📄 room_201
 │   │   │   ├── 📄 room_202
 │   │   │   ├── ...



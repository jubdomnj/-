src/
├── config.js          # ENV, LINE/Supabase clients, ค่าคงที่
├── db/bookings.js     # Supabase queries
├── handlers/
│   ├── event.js       # Webhook event router
│   └── commands.js    # Business logic
├── flex/
│   ├── welcome.js     # Welcome & Quick Reply menu
│   ├── booking.js     # Date, Time, Confirm UI
│   └── help.js        # Help page
└── helpers/reply.js   # LINE reply wrapper

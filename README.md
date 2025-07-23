# 🚀 StickerSpace — Supabase Launch Week 15 Submission

![StickerSpace Logo](./assets/banner.png)

**StickerSpace** is a full-stack social trading app where users can collect, battle, and trade virtual stickers. Built entirely with [Supabase](https://supabase.com), [Expo SDK 50](https://expo.dev), and [React Native](https://reactnative.dev), this project showcases end-to-end features like:

- Google OAuth login
- Real-time sticker battles
- Profile initialization triggers
- Trade mechanics
- Activity logs
- Edge Function powered game logic

---

## 📦 Included in This Repo

| File/Folder                                | Description |
|-------------------------------------------|-------------|
| `stickerspace_final_deployable_v2.zip`     | Fully working app ready to run in Expo Go or build with `eas build` |
| `stickerspace_final_schema_export.sql`     | All RLS policies, triggers, enum types, and edge-ready schema |
| `supabase_edge_functions_bundle.zip`       | All Supabase Edge Functions, each in `/supabase/functions/` |
| `assets/`                                  | Video thumbnail, banner, etc. |
| `README.md`                                | This file |
| `pitch_video.mp4`                          | 🎥 AI-generated pitch video for your submission |

---

## 🛠 Technologies Used

- **Supabase**
  - Postgres DB
  - RLS & Trigger Functions
  - Supabase Auth
  - Supabase Edge Functions
- **Expo SDK 50**
  - Expo Router
  - React Native + TypeScript
- **Vercel AI / AI Video Gen**
  - Final video created using AI narration + screen footage

---

## ✅ Features

- 🔐 **Google Login** via Supabase OAuth
- 🧑 **Profiles** auto-initialized via `handle_new_profile()` trigger
- 🌟 **Stickers** collectible and tradable
- ⚔️ **Battles** with live ownership & status tracking
- 🔁 **Trades** with proposer/receiver schema
- 💬 **Posts, Comments, Likes** with RLS
- 📊 **Login Activity Log** per user
- ⚙️ **Full Supabase Edge Function suite** in `/supabase/functions/`

---

## 🚀 Deployment Instructions

### 1. **Supabase Setup**
- Create a new Supabase project.
- Apply `stickerspace_final_schema_export.sql` in SQL Editor.
- Upload the contents of `supabase_edge_functions_bundle.zip` into your Supabase `/functions` folder.
- Set your environment variables:

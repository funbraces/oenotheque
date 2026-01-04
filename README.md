# 🍷 Œnothèque - Sophisticated Wine Tracking App

> A beautiful, Wallpaper magazine-inspired wine collection and tasting notes application

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/oenotheque&env=EXPO_PUBLIC_API_URL&envDescription=Backend%20API%20URL%20for%20the%20wine%20tracking%20app&envLink=https://github.com/YOUR_USERNAME/oenotheque%23environment-variables)

---

## ✨ Features

- 🍷 **Wine Collection Management** - Track your entire wine collection
- 🏛️ **Multiple Cellars** - Manage 7 named cellars (HKWV, JAS, AOG, Peak, Windshell, Octavian, 55 Degrees)
- 🔍 **Comprehensive Search** - Search wines, tasting notes, regions, varieties
- 🤖 **AI Label Detection** - Scan wine labels with GPT-4 Vision
- 📝 **Tasting Notes System** - Detailed note-taking with predefined descriptors
- ⭐ **Rating System** - Score wines 0-100
- 👨‍🍳 **Critic Scores** - Track Robert Parker, Allen Meadows, Wine Searcher scores
- 📊 **Statistics & Analytics** - Visualize your collection insights
- 📤 **Export Functionality** - Download your collection data
- 🎨 **Beautiful Design** - Wallpaper magazine-inspired aesthetic
- 🔐 **Secure Authentication** - JWT-based user authentication

---

## 🚀 One-Click Deployment

### Method 1: Deploy Button (Easiest!)

1. **Click the Deploy button above** ⬆️
2. **Connect your Vercel account**
3. **Set environment variable:**
   - `EXPO_PUBLIC_API_URL` = `https://90f36888b.na103.preview.abacusai.app/api`
4. **Deploy!** ✅

---

## 📋 Manual Deployment

### Prerequisites

- Node.js 18+ installed
- Vercel account

### Steps

1. **Clone this repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/oenotheque.git
   cd oenotheque
   ```

2. **Deploy to Vercel:**
   ```bash
   npx vercel --prod
   ```

3. **Add environment variable in Vercel Dashboard:**
   - Go to: Settings → Environment Variables
   - Add: `EXPO_PUBLIC_API_URL` = `https://90f36888b.na103.preview.abacusai.app/api`
   - Redeploy

---

## 🔧 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `EXPO_PUBLIC_API_URL` | Backend API endpoint | ✅ Yes |

**Production value:**
```
EXPO_PUBLIC_API_URL=https://90f36888b.na103.preview.abacusai.app/api
```

---

## 📱 Using the App

### Web Access

After deployment, your app will be available at your Vercel URL (e.g., `https://oenotheque.vercel.app`)

### Add to iPhone Home Screen

1. Open your Vercel URL in Safari
2. Tap the Share button (📤)
3. Tap "Add to Home Screen"
4. Name it "Œnothèque"
5. Tap "Add"

**Now it works like a native app!** 📱

### Default Login

- **Email:** funbraces@gmail.com
- **Password:** DRC1978!!!abc

---

## 🏗️ Project Structure

```
oenotheque/
├── index.html          # Entry point
├── vercel.json         # Vercel configuration
├── _expo/              # Expo build files
│   └── static/         # JavaScript bundles
├── assets/             # Fonts, icons, images
└── metadata.json       # Build metadata
```

---

## 🎨 Design Philosophy

**Inspired by Wallpaper Magazine:**

- **Minimalist & Modern** - Clean lines, generous whitespace
- **Monochrome Palette** - Black, charcoal, grey, white tones
- **Champagne Gold Accents** - Sophisticated luxury touches
- **Editorial Typography** - Serif headlines, sans-serif body
- **Gallery-like Presentation** - Museum-quality wine showcasing

---

## 🛠️ Tech Stack

### Frontend
- React Native (Expo)
- TypeScript
- React Navigation
- React Native Paper (Material Design)
- Expo Vector Icons

### Backend
- NestJS
- TypeScript
- PostgreSQL
- Prisma ORM
- JWT Authentication
- OpenAI GPT-4 Vision (via Abacus AI)

---

## 🔒 Security

- ✅ HTTPS by default (Vercel)
- ✅ JWT authentication
- ✅ Password hashing (bcrypt)
- ✅ Secure API connections
- ✅ Environment variable protection

---

## 📊 Features in Detail

### Wine Management
- Add wines with photos
- AI-powered label detection
- Manual entry with comprehensive fields
- Edit and update wine details
- Delete wines from collection
- Track cellar status (In Cellar / Tasted)

### Cellar Organization
- 7 named cellars support
- Storage location tracking
- Purchase date and price
- Estimated value tracking
- Drink window management

### Tasting Notes
- Visual appearance descriptors
- Aroma profiles
- Palate characteristics
- Custom notes
- Rating system (0-100)
- Critic scores (RP, AM, WS)

### Search & Filters
- Full-text search across wines and notes
- Filter by region
- Filter by variety
- Filter by vintage
- Filter by cellar
- Filter by status
- Filter by rating

### Statistics
- Total wines count
- Collection value
- Regional distribution
- Variety breakdown
- Average ratings
- Top rated wines

### Export
- CSV export
- JSON export
- Includes all wine data and notes

---

## 🐛 Troubleshooting

### App shows "Network Error"

**Solution:** Check environment variable
1. Vercel Dashboard → Settings → Environment Variables
2. Verify: `EXPO_PUBLIC_API_URL` = `https://90f36888b.na103.preview.abacusai.app/api`
3. Redeploy

### 404 Error on deployment

**Solution:** Check Vercel build settings
1. Settings → General → Build Settings
2. Output Directory: `.` (just a dot)
3. Build Command: (leave blank)
4. Install Command: (leave blank)

### Backend not responding

**Solution:** Wake up the backend
1. Open: https://90f36888b.na103.preview.abacusai.app/api
2. Wait 5 seconds for cold start
3. Try your app again

---

## 📝 License

Private project - All rights reserved

---

## 🙏 Credits

Built with ❤️ using:
- Expo
- React Native
- NestJS
- Vercel
- Abacus AI

---

## 📧 Support

For issues or questions, contact: funbraces@gmail.com

---

**Enjoy tracking your wine collection with Œnothèque!** 🍷✨

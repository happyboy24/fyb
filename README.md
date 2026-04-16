# FYB Profile Generator

## 🎓 What is this?
A beautiful profile card generator for FYB (Fresh Year Batch?) personalities. Fill the form, see live preview, download PNG card.

**Features:**
- Live preview as you type
- Photo upload with thumbnail
- Responsive design (mobile-friendly)
- Download high-res PNG
- Single HTML file (no build needed)

## 🚀 Quick Deploy to Netlify (Fixes 404 errors)
1. Create `_redirects` file (✅ **Already created!**):
   ```
   /*    /fyb-profile-generator.html   200
   ```
2. Drag entire `/fyb` folder to [Netlify Drop](https://app.netlify.com/drop)
   - Or CLI: `npm i -g netlify-cli && netlify deploy --prod --dir=.`
3. **All paths now work!** (e.g. yoursite.netlify.app/abc → loads app)

## 🖥️ Local Testing
```bash
cd /home/collins/fyb
python3 -m http.server 8000
```
Open [localhost:8000/test](http://localhost:8000/test) – should load app, no 404!

## 📱 Preview
![Fyb Profile](https://via.placeholder.com/600x800/1a0a00/f5c842?text=FYB+Card)

**Deployed? Share your Netlify link!** ✨

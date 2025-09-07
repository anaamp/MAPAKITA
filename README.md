# MAPAKITA — Transparency Map

**MAPAKITA** (from *map + ipakita*, "to show") is a civic-tech project that lets citizens track and scrutinize government projects on an interactive map.

🌐 Live site: [Your GitHub Pages Link Here]  

---

## ✨ Purpose
Government spending should be transparent and accessible. MAPAKITA helps the public:
- See where projects are located
- Track funding (ABC / bids)
- Scrutinize progress and status
- Ask: **Asan ang pondo?**

---

## 📍 Current Coverage
Pilot: **Baliwag, Bulacan**  
(Expanding to more areas soon!)

---

## 🗂 Data
- `data/projects.geojson` → government projects (title, agency, budget, status, barangay, coordinates)  
- `baliwag_barangay_centroids_full.json` → barangay centroid points (for auto-snapping projects to map)  

---

## 🔧 Tools included
- **OSM Prefill** → fetch barangay centroids from OpenStreetMap  
- **Centroid Editor** → manually adjust barangay centers  
- **CSV → GeoJSON** → convert project spreadsheets to map data  
- **Export Centroids CSV** → archive verified barangay data  

---

## 🚀 How to use / contribute
1. Open the live site  
2. Search, filter, and explore projects  
3. If you want to contribute:
   - Add new projects by editing `data/projects.geojson`  
   - Update barangay centroids via the editor  
   - File issues or suggestions here on GitHub  

---

✊ MAPAKITA is open-source and community-driven — because public funds deserve public scrutiny.

# 🧙‍♂️ Faerûn Mythallars Map

An interactive map of the **Netherese flying enclaves** of Faerûn, focused on the locations, fates, and histories of their **mythallars**—the arcane engines that made these cities fly.

This project visualizes one of the most iconic elements of the Forgotten Realms: the rise and catastrophic fall of Netheril.

---

## 🌍 Live Map

View the interactive version here:
👉 [https://xcza.github.io/Maps/mymap.html](https://xcza.github.io/Maps/mymap.html)

Click anywhere to add pins, or load saved data to explore the known enclaves.

---

## ✨ What This Map Shows

This map includes **30+ Netherese enclaves**, each with:

* 📍 Exact (map-relative) location
* 🧙 Founder (when known)
* 📅 Creation date (Netherese Year / DR equivalent)
* 💥 Fate (crashed, destroyed, vanished, survived, etc.)
* 🗺️ Crash site or last known location
* 📜 Lore notes and historical context

All data is sourced and structured from a custom JSON dataset. 

---

## 🎨 Legend (Pin Colors)

* 🔴 **Red** — Destroyed / Crashed during the Fall
* 🟠 **Orange** — Partially intact ruins / survivors
* ⚫ **Black** — Magical catastrophe / vaporized / anomalous
* 🟡 **Yellow** — Unknown or uncertain fate
* 🟢 **Green** — Survived (usually via divine intervention)

---

## 🏙️ Notable Enclaves

A few highlights from the dataset:

* **Xinlenal** — The first enclave, created by Ioulaum
* **Eileanar** — Karsus’s city, destroyed by his avatar spell
* **Thultanthar (City of Shade)** — Shifted into the Shadowfell and later returned
* **Ythryn** — Preserved in ice, later rediscovered as the Necropolis
* **Sakkors** — A sentient enclave with a mythallar mind
* **Doubloon** — Vanished without a trace

---

## 📂 Project Structure

```id="k8g6q1"
/
├── mymap.html          # Interactive map
├── my-map-pins.json    # Enclave dataset
├── (map image file)    # Your base map
```

---

## 📥 Using the Map

### Load existing data

1. Open the map in your browser
2. Click **📂 Load Map**
3. Select `my-map-pins.json`

### Save your own version

* Add pins or shapes
* Click **💾 Save Map** to export your own JSON

---

## ⚙️ Customization

You can easily:

* Add new enclaves to the JSON
* Edit descriptions or lore
* Change pin colors
* Replace the base map (Faerûn, regional, or custom)

---

## 🧠 Lore Notes

* Mythallars were massive arcane constructs that powered floating cities
* Most enclaves fell during **Karsus’s Folly** (−339 DR)
* A few survived via intervention by deities like Mystra or Selûne
* Some enclaves were destroyed even before the Fall due to magical disasters

---

## 🔮 Future Improvements

* Drawing tools (regions, routes, borders)
* Layer toggles (pre-Fall vs post-Fall)
* Timeline filtering
* Hover previews instead of click popups

---

## 📜 Credits

* Map data compiled from Forgotten Realms lore
* Built using Leaflet (open-source mapping library)
* JSON dataset created for this project 

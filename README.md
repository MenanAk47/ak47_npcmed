**The ultimate NPC medical emergency experience for FiveM servers.** Bring your emergency medical services to life with dynamic civilian 911 calls, two-stage patient injury progression, and realistic synchronized CPR resuscitation. Integrated with `ak47_lib` to provide effortless compatibility across ESX, QBCore, and Qbox frameworks.

---

## 🎥 Showcase
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/8a37bd57-7853-43ff-aa91-9635089acacf" />

> **[Click here to watch the full feature showcase on YouTube](https://youtu.be/XVJ4QDowm40)**

---


## 🔥 Key Features

Designed to improve roleplay immersion and economy balancing:

### 🚑 Dynamic Civilian Emergencies

* **Automated Incident Registration:** Automatically registers injured civilian peds within city parameters into the emergency network when downed, keeping emergency services active even during low player population.
* **Smart Duty Tracking & City Boundaries:** Configurable city radius and alert cooldowns prevent call spam. Incidents only trigger when paramedics are actively on duty (`/duty:on`), automatically clearing queue if all medics go off-duty.

### ⏱️ Two-Stage Injury & Mortality Mechanics

* **Progressive Critical Conditions:** Patients start in Stage 1 writhing on the ground in pain, deteriorating into Stage 2 unconsciousness with authentic knockout facial animations if left untreated too long.
* **Dynamic Survival Chance:** Configurable failure rate during Stage 2 CPR. If revival fails, the ped plays a synced failure animation, notifies the medic, and smoothly fades out before despawning.

### 🩺 Synchronized Paramedic Care & CPR

* **Interactive Triage Animations:** Medics approach the patient and trigger full examination routines, realistic patient alignment, and synchronized CPR chest compressions with matching victim reactions.
* **Ambient NPC Recovery:** Patients successfully revived will play recovery animations, vocalize ambient speech expressing gratitude to the medic, and naturally blend back into ambient traffic/pedestrian life.

### 💼 Paramedic Economy & Dispatch Integration

* **Automated Dispatch & GPS Blip:** Features immediate civilian-down dispatch notifications and temporary radius blips on the GPS map for all on-duty paramedics.
* **Configurable Financial Rewards:** Automatically rewards paramedics with configurable cash bonuses upon patient resuscitation, backed by server-side verification.

### 🛠️ Technical Excellence

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB, QBX, and various target systems (ox_target, qb-target, qtarget).
* **Highly Secure:** Built-in server-side exploit checks, including distance validation and trigger authentication, to prevent cheating.
* **Network Culling & State Synchronization:** Utilizes server-enforced distance culling overrides (10,000 unit radius) and statebags so downed NPCs remain fully synced and do not despawn prematurely.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest

---

## ⚙️ How To Install:

* Download ak47_npcmed from your cfx portal.
* Add the script in your resources folder.
* Add items based on your framework instruction.
* Add item images into inventory.
* Start the script in your server.cfg below framework files.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_npcmed](https://docs.menanak47.com/multi-framework/ak47_npcmed)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/5606222](https://menanak47.tebex.io/package/5606222)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading

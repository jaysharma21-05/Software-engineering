# 📋 SRS (Software Requirement Specification) & SPM (Software Project Management) - Hinglish Notes

## 🎯 SRS Structure: Ek Nazar Mein (Simplified)

| **Section** | **Kya hai? (In Simple Words)** |
|---|---|
| **1. Introduction** | Project ka **'Identity Card'**. Isme batate hain ki software kiske liye hai aur kitne paani mein hai (Scope). |
| **2. General Description** | **'Bird's Eye View'**. Software kiske liye hai? Use kaun karega (Users)? Isse faida kya hoga? |
| **3. Functional Req.** | **'Main Kaam'**. Input kya doge? Process kya hoga? Output kya niklega? (Jaise: Login button dabane pe Dashboard khulna). |
| **4. Interface Req.** | **'Baatcheet'**. Software dusre software ya hardware se kaise connect hoga? (API, Shared Memory, etc.). |
| **5. Performance Req.** | **'Raftaar'**. System kitna load jhel sakta hai? Error rate kitna hoga? Speed (Dynamic) vs Size (Static). |
| **6. Design Constraints** | **'Laxman Rekha'**. Limitations! Jaise: "Sirf Java use karna hai" ya "Sirf 4GB RAM pe chalna chahiye". |
| **7. Non-Functional** | **'Quality Check'**. Security kaisi hai? Kitna reliable hai? Ek phone se dusre phone pe chalega ya nahi (Portability)? |
| **8. Budget & Schedule** | **'Kharcha aur Time'**. Paisa kitna lagega aur deadline kab ki hai? |

---

## 🛠️ SRS Ke Main Components (Exam Focus)

### **1. Functional Requirements (Asli Kaam)**

Ye batata hai ki system **kya karega**.

- **Input-Output Relation:** Kaunsa button dabane par kya hona chahiye? Kaunse data se kya output aayega?
- **Ranked Order:** Sabhi requirements ko unki priority (zaroorat) ke hisaab se list kiya jata hai.
- **Details:** Isme input ka source, unit (jaise kg ya meter), aur valid range (jaise age 1-100 hi honi chahiye) sab likha hota hai.

### **2. Interface Requirements (Connect kaise hoga?)**

Software akela nahi chalta, usse dusron se baat karni padti hai.

- **User Interface:** User screen ke saath kaise interact karega?
- **Software/Hardware Interface:** Software dusre programs ya hardware devices ke saath kaise communicate karega (using codes, data streams, ya shared memory).

### **3. Performance Requirements (Speed aur Efficiency)**

System kitna fast aur load jhelne wala hoga.

- **Static Requirements:** Jo chalte huye system par asar nahi daalte (jaise: Kitni memory storage chahiye).
- **Dynamic Requirements:** Jo chalte huye system ke behaviour par asar daalte hain (jaise: Response time kitna hoga? Ek second mein kitne transactions honge?).

### **4. Design Constraints (Laxman Rekha)**

Ye wo **limits** hain jinke andar reh kar developer ko kaam karna hai.

- **Example:** "Sirf Oracle database use karna hai" ya "Sirf Linux OS par chalna chahiye."
- Isme security policies aur hardware limitations bhi aati hain.

### **5. Non-Functional Attributes (Quality Check)**

System ke "Features" nahi, balki uski **"Visheshta" (Quality)**.

- **Security:** Data safe rahega ya nahi?
- **Portability:** Kya ye Windows aur Mobile dono pe chalega?
- **Reliability:** Kya system baar-baar crash toh nahi hoga?

### **6. Preliminary Schedule & Budget (Time aur Paisa)**

Ye project ka **initial estimate** hota hai.

- Kitna time lagega (Deadline)?
- Kitna paisa kharch hoga (Total Cost)?

### **7. Appendices (Extra Masala)**

Jo main document mein fit nahi hota, wo yahan aata hai.

- **Glossary:** Mushkil words ki definition.
- **References:** Kahan se information li gayi?
- **Abbreviation:** Full forms (jaise SRS, RAM, etc.).

---

## 🎯 SRS Ka Use Kaun-Kaun Karta Hai?

| **User** | **Use Case (Kyu chahiye?)** |
|---|---|
| **Developer** | Code likhne ke liye "Guide" ki tarah. |
| **Tester** | "Test Plans" banane ke liye (check karne ke liye software sahi bana ya nahi). |
| **Project Manager** | Planning, Budgeting aur Schedule manage karne ke liye. |
| **Customer** | Ye confirm karne ke liye ki usne jo maanga tha, wahi mil raha hai. |
| **Support Staff** | Baad mein software mein koi dikat aaye toh use samajhne ke liye. |

---

## ⭐ Characteristics of a Good SRS (The "Ideal" Qualities)

Ek achha SRS kaisa hona chahiye? Bas ye keywords yaad rakho:

- **1. Correctness:** Jo likha hai wo sahi hona chahiye. Customer se review karwao taaki baad mein wo ye na bole ki "Maine ye nahi maanga tha."
- **2. Completeness:** Sab kuch cover hona chahiye (Functional + Non-Functional). Kahin bhi **"TBD" (To Be Decided)** nahi hona chahiye.
- **3. Consistency:** Do baatein aapas mein nahi bhidni chahiye. Aisa na ho ki Page 5 par likha hai "Admin can delete" aur Page 10 par likha hai "Admin cannot delete."
- **4. Unambiguous (Clear):** Ek sentence ka sirf **ek hi matlab** nikalna chahiye. "Fast response" likhne ki jagah "Response within 2 seconds" likho.
- **5. Verifiability (Testable):** Har requirement aisi honi chahiye jise check kiya ja sake. Agar verify nahi ho sakti, toh wo requirement bekaar hai.
- **6. Modifiability:** Software mein change aana pakka hai. Isliye SRS ka structure aisa ho ki bina poora document hilaaye, chote-mote changes kiye ja sakein.
- **7. Traceability:** Har requirement ka ek unique ID ho (e.g., R1, R2). Isse pata chalta hai ki ye requirement code mein kahan hai aur test case mein kahan.
- **8. Design Independence:** SRS ko sirf **"WHAT"** (Kya karna hai) par focus karna chahiye, **"HOW"** (Kaise karna hai) par nahi. Design ki tension developer ki hai.

---

# 🚀 SPM (Software Project Management) - Hinglish Guide

## SPM Kya Hai? (The Simple Logic)

Software Project Management do cheezon se bana hai: **Software** + **Management**.

Jab hum koi bada software banate hain (jaise WhatsApp, Instagram, ya koi Banking app), toh usse sirf ek insaan baith kar code nahi kar sakta. Uske liye ek poori team, bohot saara paisa, aur kaafi waqt chahiye hota hai. In sab cheezon ko sahi dhang se sambhalne ko hi **SPM** kehte hain.

---

### Ek Mazedaar Analogy: "Ghar Banana" 🏠

Socho aapko ek naya ghar banwana hai.

- Aap direct eentein (bricks) utha kar deewar khadi nahi karte.
- Pehle aap **Naksha (Design)** banwate ho.
- Phir **Budget** fix karte ho ki kitne lakh mein ghar ban jayega.
- Phir **Mazdoor aur Engineer (Team)** bulate ho.
- Beech-beech mein check karte ho ki kaam sahi chal raha hai ya nahi (**Monitoring**).

**Bas, software ke case mein ghar ki jagah "App" hoti hai aur mistri ki jagah "Developers".**

---

### SPM ke 3 Sabse Important Pillars (The Triple Constraint)

Management mein ek triangle hota hai jise manager ko humesha balance karna padta hai:

1. **Scope (Kaam):** App mein kya-kya features honge? (Agar features badhoge toh time aur paisa bhi badhega).
2. **Time (Waqt):** Client ko kab tak software deliver karna hai?
3. **Cost (Budget):** Kitne paise kharch honge? (Developers ki salary, server ka kharcha, etc.)

> **Rule:** Agar aap inme se ek bhi cheez chhedoge, toh baaki do par asar padega. Jaise agar jaldi (Time) kaam chahiye, toh zyada log lagane padenge (Cost badh jayegi).

---

### SPM Mein Project Manager Kya Karta Hai? (Step-by-Step)

1. **Project Planning:** Sabse pehle "Roadmap" banana. Kaun sa kaam pehle hoga, kaun sa baad mein.
2. **Estimation:** Yeh andaza lagana ki project kitne din mein khatam hoga aur kitna paisa lagega.
3. **Scheduling:** Team ko kaam baantna. "Rahul coding karega, Priya testing karegi."
4. **Risk Management:** Pehle se sochna ki kya gadbad ho sakti hai. (Jaise: "Agar internet band ho gaya toh?" ya "Agar client ne naya feature maang liya toh?").
5. **Quality Management:** Yeh check karna ki software "ghatiya" na bane. Usme bugs kam se kam hon.

---

### SPM Kyun Zaroori Hai?

Agar SPM nahi hoga, toh:

- Project kabhi **on-time** khatam nahi hoga.
- Team ke beech mein **jhagde** honge (kaun kya kar raha hai pata nahi chalega).
- **Paisa waste** hoga kyunki bina planning ke kaam baar-baar dohrana padega.
- End mein software **crash** ho jayega kyunki testing dhang se nahi hui hogi.

---

### Ek Chhoti si Summary

**SPM** woh kala (art) hai jisse hum technical logon (developers) aur business ki needs (client) ke beech balance banate hain taaki ek **shaandaar software** sahi **time** aur **budget** mein taiyar ho jaye.

---

## 📝 Last Updated: January 2026

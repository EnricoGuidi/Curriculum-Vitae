# CVE-  Web App Curriculum Interattivo

**CVE** è una web app sviluppata con [Flask](https://flask.palletsprojects.com/) che presenta in formato interattivo il profilo professionale

---

## 🚀 Funzionalità

- Visualizzazione dinamica del curriculum
- Sezioni tematiche (profilo, esperienze, competenze, certificazioni)
- Design responsive e moderno
- Carousel immagini (certificazioni, brevetti, sport)
- Link ai social media
- Conforme a GDPR (footer legale)

---

## 🗂️ Struttura del Progetto
/CVE/
│
├── app.py
├── requirements.txt
│
├── static/
│   ├── style.css
│   └── img/
│       ├── logo.png
│       ├── profilo.jpg
│       └── ...
│
└── templates/
    └── index.html





## ▶️ Avvio in locale (VSCode o terminale)

1. **Clona il progetto**
   ```bash
   git clone https://github.com/EnricoGuidi/Curriculum-Vitae
   cd Curriculum-Vitae

2. **Crea ambiente virtuale (opzionale ma consigliato)**

3. **Installa dipendenze**
pip install -r requirements.txt

4. **Esegui l'applicazione**
python app.py


4. **Visita nel browser**
http://127.0.0.1:5000


# 🌐 Deploy consigliato: Render.com

1. Crea un account su https://render.com
2. Collega il repository GitHub
3. Imposta:
- - Build Command: pip install -r requirements.txt
- - Start Command: python app.py
- - Runtime: Python 3.x
4. L'app sarà online e accessibile via link pubblico (es. https://insightup.onrender.com)


# 📧 Contatti

Ing. Enrico Guidi
✉️ enrico.guidi.ing@gmail.com
📞 +39 345 318 5732
🏠 Genova, Italia

# 📜 Licenza

Questo progetto è privato. I contenuti non sono distribuiti pubblicamente.
Tutti i dati personali visualizzati sono protetti secondo il Regolamento UE 2016/679 (GDPR).
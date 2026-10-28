# Laboratorium z Rachunku Prawdopodobieństwa (AI)
### Paweł Lorek
### [Uniwersytet Wrocławski](https://math.uni.wroc.pl)




## O materiałach

Listy zadań i notebooki do laboratorium z Rachunku Prawdopodobieństwa (AI). Eksperymenty i symulacje w Pythonie z wykorzystaniem NumPy i Matplotlib.

**Rok akademicki 2026/2027**

## Jak korzystać z notebooków?

### 1. Google Colab

Nie wymaga instalacji — potrzebne jest konto Google.

* Otwórz notebook na GitHubie i kliknij przycisk <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>.
* Zapisz własną kopię: **Plik → Zapisz kopię na Dysku**.
* Możesz też pobrać plik `.ipynb` i otworzyć go w [Google Colab](https://colab.research.google.com/) przez **Plik → Prześlij notebook**.

### Wyłączenie wspomagania AI

Na zajęciach należy mieć wyłączone podpowiedzi i generowanie kodu przez AI w Google Colab.

Otwórz **Narzędzia → Ustawienia** (ang. **Tools → Settings**) i przejdź do sekcji **Pomoc oparta na AI**I (ang. **AI Assistance**). Ustaw opcje zgodnie z tabelą:

| Opcja — opis po polsku | Nazwa w interfejsie angielskim | Ustawienie |
|---|---|:---:|
| Pokaż uzupełnienia kodu oparte na AI | Show AI-powered inline completions | ☐  |
| Zgoda na korzystanie z funkcji generatywnej AI| Consented to use generative AI features | ☐  |
| Ukryj funkcje generatywnej AI | Hide generative AI features | ☑  |
 

### 2. Lokalnie w Jupyterze

Zainstaluj Pythona oraz potrzebne pakiety w swoim środowisku:

```bash
python -m pip install numpy matplotlib jupyterlab
```

Pobierz wybrany notebook lub sklonuj całe repozytorium:

```bash
git clone https://github.com/lorek/RPAI_lab.git
cd RPAI_lab
```

Uruchom JupyterLab:

```bash
jupyter lab
```

W przeglądarce wybierz plik `.ipynb`. Komórki wykonuj kolejno od góry, używając **Shift+Enter** lub przycisku **▶**.

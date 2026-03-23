# 🍽️ NutriSeeker — AI Indian Meal Nutrition Analyzer

## What is this?
NutriSeeker is an AI-powered nutrition analyzer
for Indian foods. Upload a food photo and get
instant nutritional information.

## Tech Stack
- Food Detection: BLIP / LLaVA-7B
- Food Validation: CLIP
- Database: IFCT 2017 (542 Indian foods)
- Retrieval: FAISS semantic search
- Fallback: USDA FoodData Central
- Frontend: Gradio
- Backend: FastAPI
- Hosting: HuggingFace Spaces

## Team
| Member | Role |
|---|---|
| Person 1 | AI Lead |
| Person 2 | Backend Lead |
| Person 3 | Database Lead |
| Person 4 | Frontend Lead |
| Person 5 | Testing + Deployment |

## How to Run
1. Open notebooks/NutriSeeker.ipynb in Google Colab
2. Enable T4 GPU
3. Run all cells top to bottom
4. Click the Gradio link

## Inspired By
DietAI24 — Nature Communications Medicine (2025)
```

**Step 5 — Create branches**

Go to your repo → click the branch dropdown (says "main") → type each name → click Create branch:
```
Create these 6 branches:
1. dev              ← all work merges here first
2. feature/ai       ← Person 1's branch
3. feature/backend  ← Person 2's branch
4. feature/database ← Person 3's branch
5. feature/frontend ← Person 4's branch
6. feature/testing  ← Person 5's branch
```

**Step 6 — Protect main branch**
```
Settings → Branches → Add branch protection rule
Branch name: main
✅ Require pull request before merging
✅ Require 1 approval
Save
```

This stops anyone from accidentally breaking main.

**Step 7 — Add team members**
```
Settings → Collaborators → Add people
Add each team member's GitHub username
They will get an email invitation
```

**Step 8 — Create Issues for this week's tasks**

Go to Issues tab → New Issue → Create one for each person:
```
Issue 1: [AI] Get LLaVA running on RTX laptop
         Assigned to: Person 1
         Label: Week 1

Issue 2: [Backend] Set up FastAPI with 3 routes
         Assigned to: Person 2
         Label: Week 1

Issue 3: [Database] Verify FAISS working + expand foods
         Assigned to: Person 3
         Label: Week 1

Issue 4: [Frontend] Polish Gradio UI + add meal history
         Assigned to: Person 4
         Label: Week 1

Issue 5: [Testing] Collect 30 test images + test notebook
         Assigned to: Person 5
         Label: Week 1
```

---

## Then — Every Other Person Does This (Persons 2-5)

---

### 👤 Persons 2, 3, 4, 5 — Join & Setup (15 minutes each)

**Step 1 — Accept invitation**
```
Check email → Accept GitHub invitation
```

**Step 2 — Go to correct branch**
```
Go to github.com/Person1username/NutriSeeker
Click branch dropdown
Select YOUR branch:
  Person 2 → feature/backend
  Person 3 → feature/database
  Person 4 → feature/frontend
  Person 5 → feature/testing
```

**Step 3 — Connect Colab to GitHub**
```
1. Open colab.research.google.com
2. File → Open notebook → GitHub tab
3. Search: NutriSeeker
4. Open NutriSeeker.ipynb from notebooks folder
5. File → Save a copy in GitHub
6. Select YOUR branch
7. Click OK

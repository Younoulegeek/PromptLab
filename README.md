# 🎨 PromptLab – Apprendre, Créer, Maîtriser les Prompts IA

PromptLab est une plateforme interactive d'apprentissage et d’expérimentation autour des prompts d’image et de vidéo générés par IA. Conçue pour les créateurs, artistes et curieux du digital, elle combine pédagogie, génération en temps réel et gamification.

---

## 🚀 Vision du projet

Notre mission est de démocratiser l’art du prompt en proposant :

- Une interface intuitive pour créer des prompts complexes sans coder
- Un espace d’apprentissage structuré, de débutant à expert
- Une galerie d’inspiration communautaire et évolutive
- Une intégration directe avec les IA leaders du marché : **DALL·E**, **Midjourney**, **Stable Diffusion** (puis **Sora**, **Veo**, **Runway**)

PromptLab veut devenir **le Notion du prompt visuel**.

---

## 🏗️ Stack technique

| Composant       | Technologie utilisée         |
|-----------------|------------------------------|
| Frontend        | Next.js 14, React, Tailwind CSS |
| Backend         | Supabase (DB + Auth), Vercel Edge Functions |
| Génération IA   | OpenAI (DALL·E), Stability AI, Midjourney (via Discord) |
| Paiement        | Stripe                       |
| Analytics       | PostHog                      |
| UI/UX design    | Figma                        |

---

## 🧪 Fonctionnalités MVP (Phase 1 - Image)

### 🔧 Fonctionnalités principales
- ✅ **Prompt Builder interactif** (drag & drop)
- ✅ **Galerie de styles visuels** (Cyberpunk, Renaissance, etc.)
- ✅ **Bibliothèque de prompts** catégorisés (500+)
- ✅ **Test en temps réel via l'API DALL·E**

### 📚 Modules d’apprentissage
1. **Basics** : Anatomie d’un prompt image
2. **Styles** : Renaissance, Bauhaus, etc.
3. **Composition** : Lighting, angles, règle des tiers
4. **Avancé** : Negative prompts, weights, seeds

---

## ⚙️ Instructions d’installation (Dév local)

### 1. Cloner le repo

```bash
git clone https://github.com/ton-utilisateur/promptlab.git
cd promptlab

# Nutrition Science | Sarcopenia Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Sarcopenia (2026 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Sarcopenia (2026 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Risk assessment**: five-step SARC-F self-assessment, grip strength, calf circumference, and walking-speed cutoffs
- **Dietary-nutrition principles**: detailed interpretation and practical advice for 7 official principles
- **Protein guidance**: precise intake calculation, three-meal distribution, and food-equivalence exchange
- **Nutrition supplementation**: whey protein, leucine, CaHMB, and vitamin D doses and precautions
- **Regional menus**: 7 regions × 4 seasons × 3 energy levels = 84 daily menus
- **TCM dietary support**: 3 syndrome patterns and 12 dietary formulas
- **Comorbidities**: individualized dietary-nutrition adjustments for obesity, diabetes, kidney disease, and tumors
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Protein (sarcopenia) | 1.2–1.5 g/kg/day | For 60 kg, about 72–90 g/day |
| Protein per meal | 20–25 g | About one egg plus one cup of milk |
| High-quality protein share | ≥60% | At least two of three protein portions should be high-quality |
| Whey protein supplement | 20–40 g/day | About half to one scoop of protein powder |
| Calf circumference (men/women) | ≥34 cm / ≥33 cm | If not much thicker than a water bottle, pay attention |
| Grip strength (men ≥65) | ≥28.0 kg | Difficulty opening bottles is a warning sign |
| Grip strength (women ≥65) | ≥18.0 kg | Difficulty lifting 5 jin should be checked |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~07 | Seven dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-08~12 | Food choices, TCM ingredients, exchange tables, menus, and formulas | Appendices |
| KPK-13~15 | Definition, screening/diagnosis tools, and guideline use | Preface + appendices + Q&A |

## File Structure

```text
- skill.yaml: Skill configuration
- system_prompt.md: System prompt
- knowledge_base.md: KPK knowledge base with 15 knowledge points
- recipes_data.md: 7 regions and 84 daily menus
- recipes_overview.md: Menu overview and examples
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. Sarcopenia diagnosis requires comprehensive evaluation by a medical institution; the screening tools here are only preliminary risk prompts.
3. Food-medicine substances and nutrition supplements should be used under professional guidance and not taken in excessive amounts.
4. People with diabetes, chronic kidney disease, tumors, or other underlying conditions should receive professional physician and nutrition guidance.
5. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT

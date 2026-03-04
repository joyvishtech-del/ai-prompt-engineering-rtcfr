# Pediatric Nutrition Prompt  
## Using the RTCFR Prompt Engineering Framework

This repository demonstrates how to design **structured, high-quality prompts for AI systems** using the **RTCFR framework**.

The goal of this prompt is to guide an AI model to generate a **safe, culturally appropriate 7-day feeding plan for a 9-month-old baby** transitioning from milk to solid foods.

The diet follows a **South Indian vegetarian pattern** and avoids eggs, processed foods, sugar, honey, and excess salt.

---
# Use Case

Parents often struggle when transitioning babies from **milk-based feeding to solid foods**.

This prompt instructs an AI model to:

- act as a **board-certified pediatric nutritionist**
- provide **evidence-based guidance**
- generate a **structured 7-day feeding schedule**
- follow **South Indian vegetarian dietary practices**
- ensure **age-appropriate food textures and nutrition**

---

# The Prompt

## ROLE

You are a **board-certified pediatric nutritionist and infant feeding specialist** with deep expertise in infant nutrition, baby-led weaning, and South Asian dietary practices.

You specialize in helping parents transition babies from milk-based feeding to balanced solid foods while ensuring proper nutrition, digestion, and growth.

---

## TASK

Guide parents on transitioning their **9-month-old baby from primarily milk feeding to solid foods**.

Create a **structured 7-day feeding schedule** that gradually increases solid food intake and reduces dependence on milk.

Include:

- Meal timing  
- Portion guidance  
- Texture recommendations  
- Safe feeding practices appropriate for a 9-month-old baby  

---

## CONTEXT

Baby profile:

- Age: **9 months**
- Current feeding: **Mostly breast milk or formula**

Goal:

- Gradually **wean from milk**
- Transition to **nutritious solid foods**

Dietary restrictions:

- **Strictly South Indian vegetarian diet**
- **No eggs**

Avoid:

- Processed foods  
- Excess salt  
- Sugar  
- Honey  

Food texture requirements:

- Soft
- Mashed
- Easy to chew

Suggested traditional foods:

- Idli
- Dosa
- Dal
- Rice
- Vegetables
- Fruits
- Ragi

Nutrition focus:

- Iron
- Protein
- Calcium
- Healthy fats

Daily feeding pattern:

- **3 main meals**
- **2 snacks**
- **Milk feeds**

Include **hydration guidance** as well.

---

## FEW SHOT EXAMPLES

### Example Daily Structure

Morning (6:30–7:00 AM)  
Breast milk / formula

Breakfast (8:30 AM)  
Soft mashed idli with ghee and diluted sambar

Snack (10:30 AM)  
Mashed banana

Lunch (12:30 PM)  
Rice + moong dal + mashed carrot

Evening Snack (3:30 PM)  
Ragi porridge

Dinner (6:30 PM)  
Vegetable khichdi

Bedtime (8:30 PM)  
Breast milk / formula

---

### Example Texture Guidance

- Idli → mashed with warm water or dal  
- Rice → well cooked and mashed  
- Vegetables → steamed and pureed or finely mashed  
- Fruits → soft mashed  

---

### Example Nutrition Tip

Ragi porridge is rich in **calcium and iron**, making it excellent for growing babies.

---

## REPORT FORMAT

Provide the output as a **7-day feeding schedule table** with the following columns:

| Day | Time | Meal Type | Food Item | Preparation Method | Portion Size | Nutritional Benefit |

After the table include the following sections:

1. **Transition Strategy**  
   (How to gradually reduce milk feeds)

2. **Safe Foods for 9-Month Babies**  
   (South Indian dietary context)

3. **Foods to Avoid**

4. **Portion Guidelines**

5. **Signs Baby Is Ready for More Solids**

6. **Simple Homemade Recipes**  
   (3–5 examples)

---

## TONE

The response should be:

- Warm and supportive for new parents
- Practical and culturally relevant for South Indian households
- Evidence-based pediatric nutrition guidance
- Clear and simple (avoid medical jargon)

---

# How to Use This Prompt

1. Copy the prompt from this repository.
2. Paste it into an AI model such as:
   - ChatGPT
   - Claude
   - Gemini
3. Run the prompt to generate a **structured 7-day baby feeding plan**.

---

# Why RTCFR Works Better Than Simple Prompts

Basic prompts often produce **inconsistent and incomplete responses**.

RTCFR improves output quality by:

- defining **expert roles**
- providing **clear instructions**
- adding **context and constraints**
- showing **examples**
- enforcing **structured outputs**

This approach significantly improves **accuracy, structure, and reliability** of AI-generated responses.

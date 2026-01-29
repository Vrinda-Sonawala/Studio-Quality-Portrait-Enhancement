# Studio-Quality Portrait Enhancement

## Project Objective
Enhance raw human portrait images captured in uncontrolled conditions into clean, studio-style portraits.

---

## Goal
Convert a normal raw photo into a **clean and professional-looking portrait** while keeping the face natural.

The project focuses on fixing:
- Messy or cluttered background
- Low lighting or low contrast
- Slight blur
- Preserving natural skin and facial identity

---

## How the Code Works

1. **Load Image**
   - Reads the image (`myphoto.jpg`) uploaded in Google Colab.

2. **Separate Person from Background**
   - Uses OpenCV’s GrabCut method to roughly separate the person from the background.

3. **Background Blur**
   - Applies a strong blur to the background to create a portrait (bokeh) effect while keeping the subject clear.

4. **Improve Face Clarity**
   - Enhances image details to make the face look sharper and clearer.

5. **Improve Lighting**
   - Improves brightness and contrast so the image looks more balanced and studio-like.

6. **Smooth Skin**
   - Applies light smoothing to reduce noise while keeping important details like eyes and hair clear.

7. **Final Output**
   - Combines all steps to generate a natural-looking studio-style portrait.

---

## Input
- Raw human portrait image (`myphoto.jpg`) uploaded in Google Colab.

---

## Output
- Enhanced portrait image with:
  - Blurred background
  - Clear and sharp face
  - Improved lighting and contrast
  - Natural-looking skin
  - Same facial identity

---

## Tools & Technologies
- Python  
- OpenCV  
- NumPy  
- Google Colab  


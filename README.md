# Round-1-Machine-Learning-Engineer-Vrinda

This repository contains the solution for **Question 1** of the Round 1 assessment for the **Machine Learning Engineer role at FOG**.

## Question 1: Convert Raw Human Image into Studio-Quality Portrait

### Objective
Enhance raw human portrait images captured under uncontrolled conditions into **studio-quality portraits** using **computer vision**.

### Goal
Turn a normal raw photo into a **professional-looking portrait**.  
Fix problems like:

- Messy or cluttered background
- Low lighting or low contrast
- Slight blur
- Keep the face and skin natural

### How the Code Works

1. **Load Image**
   - Reads the image `myphoto.jpg` uploaded in Colab.

2. **Separate Person from Background**
   - Uses OpenCV's **GrabCut** to select the person in the photo and separate them from the background.

3. **Blur Background**
   - Makes the background soft and blurry while keeping the person clear.

4. **Make Face Clearer**
   - Improves sharpness and details of the face.

5. **Improve Lighting**
   - Makes the lighting and contrast look better and natural.

6. **Smooth Skin**
   - Smooths the skin slightly but keeps eyes, lips, and hair clear.

7. **Final Image**
   - Combines all steps to make a natural studio-style portrait.

### Input
- Raw human portrait image (`myphoto.jpg`) uploaded in **Colab Files**.

### Output
- A studio-quality portrait with:
  - Blurred background
  - Clear face
  - Natural-looking skin
  - Same facial identity

### Dependencies
- Python 3
- OpenCV (`opencv-python`)  
- NumPy  

Install in Colab:

```python
!pip install opencv-python numpy

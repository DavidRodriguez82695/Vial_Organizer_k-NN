# Put all files with "Image -" in front of it to an Image folder and merge any that are numerical.





# Vial Organizer with k-NN Machine Learning

This project presents a simple yet effective machine learning-based approach to organizing vials based on their cap colors using the k-Nearest Neighbors (k-NN) algorithm. The system is built around a grid-style vial holder, where each slot may contain a vial with a colored cap (Red, White, Blue, Black, or No Cap). The goal is to detect vial cap types from images and reorganize them according to a target logic (e.g., sorted Red-White-Blue by column).

---

## 🧠 Project Summary

- **Input**: Images of a 3×3 vial holder generated with predefined vial cap overlays
- **Output**: Classification of each vial slot by cap color (Red, White, Blue, Black, No Cap, or Empty)
- **Focus**: Only Red, White, and Blue vials are used for sorting; others are ignored
- **Model**: k-Nearest Neighbors (k-NN) classifier trained on average RGB values
- **Grid Logic**: Fixed hit boxes are used to extract average color data from each slot

---

## 🧰 Technologies Used

- Python 3.13
- Jupyter Notebook
- `numpy`, `PIL`, `tqdm`
- k-Nearest Neighbors via `sklearn`
- Custom color calibration using predefined hit box regions

---

## 📂 File Structure


---

## 🔍 Key Features

- Extracts vial slot regions using fixed grid offsets and dimensions
- Averages pixel colors to determine dominant RGB values
- Trains a k-NN model to classify vial types based on cap color
- Ignores vials with black caps or no caps
- Designed for use with a robotic sorting system or simulation

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/vial-organizer-knn.git
   cd vial-organizer-knn

2. Launch the notebook:

jupyter notebook "Vial Organizer with k-NN Machine Learning.ipynb"

3.Run the cells to:
    Load image data
    Extract hit box regions
    Train the k-NN model
    Predict cap types across the 3x3 grid

📸 Example Output
Coming soon...

🧪 Future Improvements
Improve classification accuracy with CNN or YOLO-based methods

Implement real-time camera input

Extend sorting logic to include custom configurations

Integrate with a robotic arm or simulation environment

📝 License
This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

👥 Team Members
Jyothsna Saripalli
Chaim U Leiter
David Rodriguez
Carlos Garrastegui
Yadriam Morgado
Mario Zeledon
Ali Gasanov
Adonikam Hibbert


👤 Poster
David Rodriguez
Florida International University — Mechanical Engineering
Reach out via LinkedIn or GitHub Issues for questions or collaborations!


---

Let me know if you want to include example images, GIFs, or model performance plots — I can help you add those in too!



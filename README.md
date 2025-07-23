  ********* IDE Mask Effect Parameters*********

## 📌 Overview:
This project investigates the fabrication and characterization of P-Si/ZnO heterojunction diodes, focusing on the impact of contact geometry on key electrical parameters.
 
## ✨ Project Objectives:
**Fabricate** P-Si/ZnO heterojunction diodes using both circular and IDE contact masks. 
**Characterize** the diodes' electrical properties through I-V measurements from -2V to 2V in a dark room environment.
**Analyze and Compare** key diode parameters, including the ideality factor (n), reverse saturation current (Idss), and built-in potential (Vbi). 
**Investigate** the effect of contact geometry on current spreading and overall device performance. 

## 🔬 Methodology & Fabrication:

The diodes were fabricated through a standard microfabrication workflow:

1. **Substrate Cleaning:** Wafers of p-Si underwent a rigorous cleaning process including Piranha clean, RCA clean (SC-1 and SC-2), and an HF dip to remove organic, inorganic, and native oxide contaminants. 
2. **ZnO Thin Film Deposition:** A ZnO thin film was deposited onto the p-Si substrates using an RF Magnetron Sputtering system.
3. **Aluminum Contact Deposition:** Aluminum contacts were deposited onto the ZnO layer via a Thermal Evaporation system, using shadow masks to define the circular and IDE patterns.

   ## 📊 Results & Key Findings

The I-V characteristics were measured using a **Keysight B1500A Semiconductor Device Analyzer**. The analysis revealed a clear trade-off in performance based on contact geometry.
| Parameter | Circular Mask | IDE Mask |
| :--- | :---: | :---: |
| **Ideality Factor (n)** | 2.28  | 2.13  |
| **Saturation Current (Idss)** | 2.48 x 10⁻¹² A  | 3.68 x 10⁻⁹ A  |
| **Built-in Potential (Vbi)** | 1.58 V  | 1.07 V  |
#### I-V Characterization Curves
*The graphs attached in the IMAGES folder show the raw measurement data for both diode types.

## 結論 (Conclusion)

The study successfully demonstrated the trade-offs associated with using an IDE contact for a P-Si/ZnO vertical heterojunction diode.

**Improved Ideality:** The IDE mask led to a slight reduction in the ideality factor, suggesting a move toward more ideal diode behavior, potentially due to more uniform current distribution. 

**Increased Leakage:** However, the IDE mask also resulted in a saturation current (leakage) that was approximately three orders of magnitude larger, likely due to the increased contact area and perimeter providing more pathways for surface leakage. 

**Reduced Built-in Potential:** A noticeable decrease in the built-in potential ($Vbi$) was observed for the IDE contact.This could be attributed to changes in the effective junction area or other interface effects introduced by the IDE geometry.

**Overall Impact:** While IDEs are often used to reduce series resistance, this work shows that for vertical diodes, they can introduce undesirable effects like higher leakage current.  This highlights the critical need to match contact geometry to device architecture and performance goals.

## 🛠️ Learning Outcomes

This project provided hands-on experience in semiconductor device fabrication , electrical characterization, and data analysis to extract key device parameters and critically evaluate the impact of design choices on device performance. 

---
## 💡 Future Scope

**Noise Reduction & Measurement Optimization:** Implement an improved measurement setup to minimize the electrical noise observed during I-V characterization, allowing for more precise parameter extraction
**Advanced Interface Characterization:** Investigate the P-Si/ZnO interface properties more deeply to better understand the non-ideal transport mechanisms and the sources of leakage current.
 **Optimization of IDE Geometry:** Fabricate and test devices with varying IDE finger widths and spacing to find an optimal geometry that balances the benefits of lower resistance with the drawback of increased saturation current.

## 👥 Authors

This project was a collaborative effort by:

* **Yashika Tyagi** ([LinkedIn](https://www.linkedin.com/in/yashika-tyagi-487a71284/)) ([GitHub](https://github.com/Yashika-25))
**Ojaswini Sharma**
**Sarthak Pratap Singh**





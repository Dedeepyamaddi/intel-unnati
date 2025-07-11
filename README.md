# intel-unnati
📷 Image Sharpening using Knowledge Distillation
This project demonstrates how to enhance blurry images using a student-teacher neural network architecture powered by Knowledge Distillation. The model learns to reconstruct sharp images from degraded ones while maintaining high SSIM (Structural Similarity Index) scores. Executed entirely in Google Colab, the project provides a complete pipeline — from preprocessing and training to evaluation and reporting.

🚀 Key Features
🔧 Custom LightDnCNN architecture for both teacher and student networks
🧠 Knowledge Distillation training approach
📉 Real-time training loss tracking
📈 SSIM-based evaluation for image quality
🖼️ Enhanced output image saving
📂 Generates a PDF report with training metrics and SSIM score
✅ Achieved 94.66% average SSIM
📊 Result Summary
✅ Average SSIM: 94.66%
📑 PDF Report Generated: report.pdf
🧠 Model Saved: student_model.pth



🛠️ Technologies Used
Python
PyTorch
PIL & OpenCV
scikit-image (SSIM)
FPDF (for PDF generation)
Google Colab (Execution Environment)


📄 Output Examples
Enhanced images: enhanced_output/
SSIM JSON: mos_feedback.json
Model: student_model.pth
PDF Report: report.pdf

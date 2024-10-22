This repository is currently under development and focuses on fine-tuning LayoutLMv3 on the SERIO dataset to improve invoice understanding through key entity extraction. The goal of the project is to accurately extract crucial information from invoices, such as company name, date, address, and total, using the power of LayoutLMv3, a transformer model capable of interpreting both text and document layout.

Key Features:
Dataset: SERIO dataset for structured invoice information extraction.
Model: Fine-tuning LayoutLMv3, a model that understands document structure and layout.
OCR Input: The model processes OCR-processed files, avoiding the need for real-time OCR.
Outputs: JSON format response with extracted bounding boxes, company name, date, address, and total.
Current Status:
Development Phase: The fine-tuning of LayoutLMv3 is in progress, with ongoing improvements in model performance and data handling.
Upcoming: In the coming days, the project will transition into the deployment phase, which will include:
API setup for easy integration
Full end-to-end functionality for submitting OCR files and receiving structured JSON responses
Stay tuned for updates as we move towards deployment!


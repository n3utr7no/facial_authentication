Project structure

*Facial Recognition/application_data/*
- `input_image/`  
  Folder containing the input image to be verified.

- `verification_images/`  
  Folder with images used for real-time verification.


*Facial Recognition/data/*
- `anchor/`  
  Anchor/reference images.

- `positive/`  
  Images of the same person as the anchor.

- `negative/`  
  Images of different individuals.



*Facial Recognition/training_checkpoints/*  
Directory to save training checkpoints.


*Facial Recognition/siamese_model.keras*  
Serialized trained Siamese model.



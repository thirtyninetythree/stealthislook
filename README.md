# stealthislook

Upload a photo of clothes and use google lens to get those same clothes or close enough - steal this look. 

- **Image Upload**: Drag and drop your fashion photo
- **Item Detection**: Automatically identify clothing and accessories
- **Smart Cropping**: Precisely extract individual fashion items
- **Reverse Image Search**: Find similar items across online stores

### TODO
- Detect fashion items and accessories ✅
- Crop fashion items ✅
- Search for items online using Google Lens or tiny eye API(currently done manually)

# Samples

## Original Image
![model](https://github.com/user-attachments/assets/33e3a7b5-3703-4c9c-9dc6-d4569a5e9cf1)
Some cropped sections are small but the search still works for them. 

## Detected Fashion Segments

| Segment | Cropped Image| Search Results |
|---------|--------------|------------|
| Segment 1 | ![dress_segment (1)](https://github.com/user-attachments/assets/5681247c-0d0d-4cbf-9e51-2ea275b8aed4)| ![download (5)](https://github.com/user-attachments/assets/51c5c141-0b90-435b-baae-a10a7e5cc453) ![download (6)](https://github.com/user-attachments/assets/dd27e8fa-5e9d-4af3-bbe6-389f3dae8518) ![download (7)](https://github.com/user-attachments/assets/c954d573-49ce-4e7c-839c-1ce9c9a942e3)
| Segment 2 | ![sunglasses_segment (1)](https://github.com/user-attachments/assets/a438118b-f1bf-48e3-9bb5-5638038fc685) | ![download (8)](https://github.com/user-attachments/assets/eeea16ae-457f-4016-97e9-5521033926dd) ![download (9)](https://github.com/user-attachments/assets/3b0954a9-55e3-4636-808c-62da7bf199b4) ![download (10)](https://github.com/user-attachments/assets/3dbe9085-0457-437b-a6ce-ac9d60716277)
| Segment 3 | ![scarf_segment](https://github.com/user-attachments/assets/fc8b5a42-ac00-4982-9fad-7bceb29b295d) | ![download (11)](https://github.com/user-attachments/assets/9d2976ad-c129-4c7e-8d0d-76d7294fbb59) ![download (12)](https://github.com/user-attachments/assets/cc215975-9453-4f98-a55b-52ddab28c655) ![download (13)](https://github.com/user-attachments/assets/3af88fce-e70a-4322-9898-97d31becc155)

## Original Image
![premium_photo-1673210886161-bfcc40f54d1f](https://github.com/user-attachments/assets/bc123ede-0999-438f-84ec-6648b66b144a)

It is prone to errors such as below, the model's face is cropped but there are no fashion accessories on the face. No search was done on his face

## Detected Fashion Segments

| Segment | Cropped Image| Search Results |
|---------|--------------|------------|
| Segment 1 | ![sunglasses_segment (2)](https://github.com/user-attachments/assets/2df208ab-2ee4-42bb-924c-7e6bbd4f1952)
| ![download (16)](https://github.com/user-attachments/assets/48de08e5-5d53-44a2-9720-673b17ea2669)
![download (15)](https://github.com/user-attachments/assets/ccb0c560-4265-4db9-bace-4786bdd03bc3)
![download (14)](https://github.com/user-attachments/assets/741d94ce-45f1-4edc-8ce1-6ae83262ca8a)

| Segment 2 | ![scarf_segment (1)](https://github.com/user-attachments/assets/9bddf6e1-e54a-4397-8691-8be4664a3871)
| 





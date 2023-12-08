# Dreambooth
Fine-Tuning Stable Diffusion Model With Dreambooth

1. Dữ liệu huấn luyện:
   - crawl dữ liệu với BingImageCrawler
   ![image](https://github.com/LiZi310702/Dreambooth/assets/119061458/c2f39a0b-247d-4a90-b095-d3ec61e9a5a1)
![Pic (29)](https://github.com/LiZi310702/Dreambooth/assets/119061458/98a2557c-5d93-4803-96c0-aab73a024d0b)


3. Tiền xử lí dữ liệu
   - Xử lí kích thước dữ liệu với BIRME
     ![image](https://github.com/LiZi310702/Dreambooth/assets/119061458/d0346a65-29e2-4052-a852-3e4a0cd063a6)

4. Huấn luyện với Colab
   https://colab.research.google.com/drive/15i53i5To83EpsanAGIsx9mbY4hUbuWyB#scrollTo=K6xoHWSsbcS3
   Thông số:
   + Model name: SG161222/Realistic_Vision_V2.0
   + Branch: man
   + Instance_promt: Photo of Jennie woman
   + class_promt: photo of Jennie
   + training steps: 800
   + learning rate: 1e-6
6. Output: checkpoint
   https://drive.google.com/drive/folders/1-6Y2KqFkGGTKzP0EzcYRFsxfaiUqFEpA?usp=sharing

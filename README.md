# Dreambooth
Fine-Tuning Stable Diffusion Model With Dreambooth

1. Dữ liệu huấn luyện:
   - crawl dữ liệu với BingImageCrawler
   ![image](https://github.com/LiZi310702/Dreambooth/assets/119061458/c2f39a0b-247d-4a90-b095-d3ec61e9a5a1)
   ![Pic (29)](https://github.com/LiZi310702/Dreambooth/assets/119061458/98a2557c-5d93-4803-96c0-aab73a024d0b)

   ![Pic (23)](https://github.com/LiZi310702/Dreambooth/assets/119061458/f6d08d13-c351-4dd2-91c1-83498f2506a4)
   ![Pic (43)](https://github.com/LiZi310702/Dreambooth/assets/119061458/3a8c8307-de22-418a-818a-57dbd3944afe)
   
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
7. Output picture:
   ![1](https://github.com/LiZi310702/Dreambooth/assets/119061458/2ddf6814-cbd1-4c6b-961e-ccf48ce7c8f7)
   ![00009-627937792 (1)](https://github.com/LiZi310702/Dreambooth/assets/119061458/099168c8-9f6b-439c-aef6-1b288b3e1698)
   ![2](https://github.com/LiZi310702/Dreambooth/assets/119061458/ea3f1dbc-b0dd-4097-bd61-ed554e4253a7)
   ![image](https://github.com/LiZi310702/Dreambooth/assets/119061458/43ca8065-1f1f-4e42-9cdf-1c27980035cc)

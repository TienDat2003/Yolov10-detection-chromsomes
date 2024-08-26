Sử dụng mô hình yolov10 để detect chromsomes

Input: https://drive.google.com/drive/folders/1-c32WI8j9cq-ACk7RFHVqff2DuZ8O0Oj?usp=sharing

      - Dữ liệu gồm 2000 ảnh và file txt, được trích xuất từ bộ dữ liệu An Open Dataset of Annotated Metaphase Cell Images for Chromosome Identification

Kết quả huấn luyện: 

          lr/pg0 4e-05
          
          lr/pg1 4e-05
          
          lr/pg2 4e-05
          
          metrics/mAP50(B) 0.9857
          
          metrics/mAP50-95(B) 0.72179
          
          metrics/precision(B) 0.96461
          
          metrics/recall(B) 0.95771
          
          model/GFLOPs 8.393
          
          model/parameters 2707430
          
          model/speed_PyTorch(ms) 2.879
          
          train/box_loss 1.76443
          
          train/cls_loss 0.74791
          
          train/dfl_loss 1.90712
          
          val/box_loss 2.04867
          
          val/cls_loss 0.72624
          
          val/dfl_loss 2.00746

# Aerial object Detection
Project focused on aerial object detection. 

The dataset used is SkyFusion that contains satelite images. 

The goal of this project is to draw a border box around objects and classify them.

Created one model from scratch with 2 heads: one for the border box output, the other one makes classification. 

Used a custom loss function: border box's loss is calculated by smooth l1 loss and classification's loss is calculated by cross entropy loss.

Then I used transfer learning with Fast RCNN model.

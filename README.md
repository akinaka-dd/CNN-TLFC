# CNN-TLFT
**Transfer learning (Fine-tuning) of a CNN model**

## H&E stain image
### Fine-tuning
Train the entire model (ResNet18+ImageNet) with new data.
<table>
<tr>
<td><img width="200px" src="img/FT/FFPE_LUAD_3_B_x10_sample_2k.jpg"></td>
<td><img width="200px" src="img/FT/FFPE_LUAD_3_B_x10_predict_grid_2k.jpg"></td>
<td><img width="200px" src="img/FT/FFPE_LUAD_3_B_x10_predict_rect_2k.jpg"></td>
</tr>
</table>

### Transfer learning (in its narrow sense)
Train the last layer of the model (ResNet18+ImageNet) with new data.
<table>
<tr>
<td><img width="200px" src="img/TL/FFPE_LUAD_3_B_x10_sample_2k.jpg"></td>
<td><img width="200px" src="img/TL/FFPE_LUAD_3_B_x10_predict_grid_2k.jpg"></td>
<td><img width="200px" src="img/TL/FFPE_LUAD_3_B_x10_predict_rect_2k.jpg"></td>
</tr>
</table>

## TEM (Transmission electron microscope) image
<table>
<tr>
<td><img width="200px" src="img/TEM/MCM-Pt852-1232-x11500_sample_2k.jpg"></td>
<td><img width="200px" src="img/TEM/MCM-Pt852-1232-x11500_predict_grid_2k.jpg"></td>
<td><img width="200px" src="img/TEM/MCM-Pt852-1232-x11500_predict_rect_2k.jpg"></td>
</tr>
</table>

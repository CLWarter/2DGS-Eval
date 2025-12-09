Under ShowImages\Output i have subfolders

enableShadingCOS - only shading with fmaxf
ShadingNormalGradCOS - shading with fmaxf and backprop of normal gradient ect...

enableShadingABS - shading with fabsf of cos (meaning backlighting or wrongly directed normals still results in shading)
ShadingNormalGradABS - with backprop again

Normal2DGS - without a change from original code

inside there are the output folders e.g. "13a57ced-8" and inside there is the training output and an export_ folder that contains the exported images (made by new script export_maps.py)
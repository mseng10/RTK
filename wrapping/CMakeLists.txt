itk_wrap_module(RTK)

set(WRAPPER_SUBMODULE_ORDER
  itkFixedArrayRTK
  itkVectorRTK
  itkCovariantVectorRTK
  itkPointRTK
  itkContinuousIndexRTK
  itkMatrixRTK
  itkVariableLengthVectorRTK
  itkImageBaseRTK
  itkImageRTK
  itkCudaImage
  itkVectorImageRTK
  itkImageSourceRTK
  itkImageToImageFilterRTK
  itkCudaImageToImageFilter
  itkInPlaceImageFilterRTK
  itkCudaInPlaceImageFilter
  rtkForwardProjectionImageFilter
  itkPyBufferRTK
)

itk_auto_load_submodules()
itk_end_wrap_module()

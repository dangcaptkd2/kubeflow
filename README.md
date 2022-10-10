# kubeflow
Build data and model pipeline using kubeflow

This is a repo to save code relate to kubeflow. 
Notes:
  - Import all the necessary by the function in that function.
  - To share a common volume between components, use `step2 = component_step2.add_pvolumes({"/data": data_op.volume.after(step1)})`
  - 1 special thing is that the model in this repo is build base on `pytorch lightning`
  

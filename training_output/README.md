# Training output
 Here we share the resulst of our training. Please find the files in the following link https://syncandshare.lrz.de/getlink/fi6vrL9FpeSM2hbzySDrnw/datasets_files . Each of our training runs produced a directory with a name 'HumanoidImitation_DD-MM-hh-mm-ss' with the respective time of creation. Each folder has a folder 'nn', a folder 'summaries' and a file 'run_config.yaml'. 'nn' contains the checkpoints for the weights of the neural network. 'summaries' has the logs of tensorboard. 'run_config.yaml' describes which training configuration we used.

 To make clear which training configuration corresponds to which fold, here we give a list. Please, take into consideration that sometimes we had to stop the training and then resume it later. Therefore, some configurations have more than one folder assigned

- **HumanoidImitation_11-06-12-25-55** torque control, r<sub>t,1</sub>, 36Hz, tracker setup H+2C, ParSet1 and 233334 training epochs.
- **HumanoidImitation_15-06-18-49-50** torque control, r<sub>t,2</sub>, 36Hz, tracker setup H+2C, ParSet1 and 233334 training epochs.
- **HumanoidImitation_20-06-16-24-51+HumanoidImitation_23-07-08-39-31** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+2C, ParSet1 and 233334 training epochs.
- **HumanoidImitation_19-06-01-53-04** torque control, r<sub>t,1</sub>, 36Hz, tracker setup H+2C, ParSet2 and 233334 training epochs.
- **HumanoidImitation_14-06-16-45-17+HumanoidImitation_18-06-05-01-55** torque control, r<sub>t,2</sub>, 36Hz, tracker setup H+2C, ParSet2 and 233334 training epochs.
- **HumanoidImitation_20-06-06-19-02+HumanoidImitation_21-07-20-51-40** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+2C, ParSet2 and 233334 training epochs.
- **HumanoidImitation_09-07-08-30-33** torque control, r<sub>t,1</sub>, 72Hz, tracker setup H+2C, ParSet1 and 100000 training epochs.
- **HumanoidImitation_07-07-18-24-42** torque control, r<sub>t,1</sub>, 72Hz, tracker setup H+2C, ParSet2 and 100000 training epochs.
- **HumanoidImitation_03-07-06-17-52** torque control, r<sub>t,2</sub>, 72Hz, tracker setup H+2C, ParSet2 and 100000 training epochs.
- **HumanoidImitation_02-07-20-53-34** pd-control, r<sub>t,2</sub>, 72Hz, tracker setup H+2C, ParSet2 and 100000 training epochs.
- **HumanoidImitation_14-07-19-12-29+HumanoidImitation_17-07-15-53-22** pd-control, r<sub>t,2</sub>, 72Hz, tracker setup H+2C, ParSet2 and 233334 training epochs.

- **HumanoidImitation_24-06-23-54-14** torque control, r<sub>t,1</sub>, 36Hz, tracker setup H, ParSet1 and 100000 training epochs.
- **HumanoidImitation_25-06-12-19-56** torque control, r<sub>t,1</sub>, 36Hz, tracker setup H+4C, ParSet1 and 100000 training epochs.
- **HumanoidImitation_01-07-07-25-38** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H, ParSet2 and 100000 training epochs.
- **HumanoidImitation_29-06-03-38-01** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+4C, ParSet2 and 100000 training epochs.
- **HumanoidImitation_06-07-08-03-53+HumanoidImitation_07-07-18-01-21** pd-control, r<sub>t,2</sub>, 72Hz, tracker setup H, ParSet2 and 100000 training epochs.
- **HumanoidImitation_05-07-20-07-52** pd-control, r<sub>t,2</sub>, 72Hz, tracker setup H+4C, ParSet2 and 100000 training epochs.


- **HumanoidImitation_11-07-03-23-10** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+2C, ParSet2, 100000 training epochs and extra dancing movements.
- **HumanoidImitation_30-06-10-19-08** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+4C, ParSet2, 100000 training epochs and extra dancing movements.
- **HumanoidImitation_13-07-02-17-13+HumanoidImitation_14-07-16-48-52** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+2C, ParSet2, 100000 training epochs and extra jumping movements.
- **HumanoidImitation_09-07-05-04-58** pd-control, r<sub>t,2</sub>, 36Hz, tracker setup H+4C, ParSet2, 100000 training epochs and extra jumping movements.

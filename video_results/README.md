# Video Results

In this folder we collect the videos showing the results of our experiments. Please follow the links to the corresponding videos and read the respective descriptions

## Results of: Different Training Configurations

- [This video](rew_rt1_vs_rt2_sync_max.mp4) shows a motion of walking of the Basic_ES set in the first row. The common training parameters for the agents were the ParSet2 parameter set, torque control and 36Hz step frequency. Here we compare the results of r<sub>t,1</sub> in row 2 against r<sub>t,2</sub> in row 3.
- [This video](control_to_vs_pd_sync_max.mp4) shows a standing motion of the Basic_ES set in the first row. The common training parameters for the agents were ParSet2 parameter set, r<sub>t,2</sub> reward and 36Hz step frequency. Here we compare the results of control with torque in row 2 against PD-control in row 3.
- [This video](bandai_que_vs_alt_altbetter_sync_max.mp4) shows a running motion of the Basic_ES set in the first row. The common training parameters for the agents were PD-control, r<sub>t,2</sub> reward and 36Hz step frequency. Here we compare the results of ParSet1 in row 2 against ParSet2 in row 3.
- [This video](lafan_que_vs_alt_quebetter_sync_max_dch.mp4) shows a running motion of the LAFAN_ES set in the first row. The common training parameters for the agents were PD-control, r<sub>t,2</sub> reward and 36Hz step frequency. Here we compare the results of ParSet1 in row 2 against ParSet2 in row 3.
- [This video](diff_rt2_alt_to_36_vs_72sync_max_dch.mp4) shows a walking motion of the Basic_ES set in the first row. The common training parameters for the agents were torques control, r<sub>t,2</sub> reward and ParSet2. Here we compare the results of 36Hz in row 2 against 72Hz in row 3.
- [This video](sim_rt2_alt_pd_36_vs_72sync_max_dch.mp4) shows a walking motion of the Basic_ES set in the first row. The common training parameters for the agents were PD-control, r<sub>t,2</sub> reward and ParSet2. Here we compare the results of 36Hz in row 2 against 72Hz in row 3.

## Results of: Different Amount of Trackers
- [This video](questsim_sync_max.mp4) shows a conversation motion of the Basic_ES set in the first row. The agents trained with QuestSimConf. Here we compare the results of H in row 2 against H+2C in row 3 and H+4C in row 4.
- [This video](par_sync_max_dch.mp4) shows a conversation motion of the Basic_ES set in the first row. The agents trained with AltConf. Here we compare the results of H in row 2 against H+2C in row 3 and H+4C in row 4.
- [This video](72par_sync_max_dch.mp4) shows a hand wavinf motion of the Basic_ES set in the first row. The agents trained with AltConf(72Hz). Here we compare the results of H in row 2 against H+2C in row 3 and H+4C in row 4.
- [This video](waa_par_sync_max_dch.mp4) shows a walking and aiming motion of the LAFAN_ES set in the first row. The agents trained with AltConf. Here we compare the results of H in row 2 against H+2C in row 3 and H+4C in row 4.
- [This video](w2s1_72par_sync_max_dch.mp4) shows a walking motion of the LAFAN_ES set in the first row. The agents trained with AltConf(72Hz). Here we compare the results of H in row 2 against H+2C in row 3 and H+4C in row 4.
- [This video](w3s2_questsim_sync_max_dch.mp4) shows a standing motion of the LAFAN_ES set in the first row. The agents trained with QuestSimConf. Here we compare the results of H in row 2 against H+2C in row 3 and H+4C in row 4.
## Results of: Real-time imitation
First we have the results using the headset and 2 controllers (H+2C):
- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet1, torque control, r<sub>t,1</sub> reward and 36Hz. [This video](greetings_torque_rt1_QuestSimPar_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](greetings_torque_rt1_QuestSimPar__233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet1, torque control, r<sub>t,1</sub> reward and 36Hz. [This video](eight_walk_torque_rt1_QuestSimPar_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](eight_walk_torque_rt1_QuestSimPar_233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet1, torque control, r<sub>t,1</sub> reward and 36Hz. [This video](jog_torque_rt1_QuestSimPar_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](jog_torque_rt1_QuestSimPar__233_sync_max.mp4) after 233333 epochs.


- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet2, torque control, r<sub>t,2</sub> reward and 36Hz. [This video](greetings_torque_rt2_AltPar_100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](greetings_torque_rt2_AltPar_233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet2, torque control, r<sub>t,2</sub> reward and 36Hz. [This video](eight_walk_torque_rt2_AltPar_100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](eight_walk_torque_rt2_AltPar_233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet2, torque control, r<sub>t,2</sub> reward and 36Hz. [This video](jog_torque_rt2_AltPar_100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](jog_torque_rt2_AltPar_233_sync_max.mp4) after 233333 epochs.

- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet1, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](greeting_PD_rt2_QuestSimPar__36Hz__100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](greetings_PD_rt2_QuestSimPar233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet1, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](eight_walk_PD_rt2_QuestSimPar__36Hz__100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](eight_walk_PD_rt2_QuestSimPar_233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet1, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](jog_PD_rt2_QuestSimPar__36Hz__100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](jog__PD_rt2_QuestSimPar_233_sync_max.mp4) after 233333 epochs.

- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](greeting_PD_rt2_AltPar___36Hz_100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](greetings_PD_rt2_AltPar___36Hz__233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](eight_walk_PD_rt2_AltPar___36Hz_100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](eight_walk_PD_rt2_AltPar___36Hz__233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](jog_PD_rt2_AltPar___36Hz_100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](jog_PD_rt2_AltPar___36Hz__233_sync_max.mp4) after 233333 epochs.


- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 72Hz. [This video](greetings_PD_rt2_AltPar___72Hz__100__sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](greetings_PD_rt2_AltPar___72Hz__233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 72Hz. [This video](eight_walk_PD_rt2_AltPar___72Hz__100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](eight_walk_PD_rt2_AltPar___72Hz__233_sync_max.mp4) after 233333 epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 72Hz. [This video](jog_PD_rt2_AltPar___72Hz__100_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs and [this video](jog_PD_rt2_AltPar___72Hz__233__sync_max.mp4) after 233333 epochs.

Next, we have the results using only the headset (H):

- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet1, torque control, r<sub>t,1</sub> reward and 36Hz. [This video](greetings_torque_rt1_QuestSimPar__one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet1, torque control, r<sub>t,1</sub> reward and 36Hz. [This video](eight_walk_torque_rt1_QuestSimPar__one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet1, torque control, r<sub>t,1</sub> reward and 36Hz. [This video](jog_torque_rt1_QuestSimPar__one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.

- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](greetings_PD_rt2__AltPar___36Hz___one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](eight_walk_PD_rt2__AltPar___36Hz___one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 36Hz. [This video](jog_PD_rt2__AltPar___36Hz___one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.

- Here we show the real-time imitation of a greeting motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 72Hz. [This video](greetings_PD_rt2__AltPar___72Hz___one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.
- Here we show the real-time imitation of a walking motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 72Hz. [This video](eight_walk_PD_rt2__AltPar___72Hz___one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.
- Here we show the real-time imitation of a jogging motion. The agent was trained with ParSet2, PD-control, r<sub>t,2</sub> reward and 72Hz. [This video](jog_PD_rt2__AltPar___72Hz___one_sync_max.mp4) depicts the imitation of the policy after 100000 training epochs.


## Results of: Additional Motion Types
- [This video](dance_dance2_subject2_sync_max_dch.mp4) shows a dance motion of the LAFAN_Dance_ES set in the first row. The agents trained with AltConf and additional movements of the dance category. We show the results of H+2C in row 2 and H+4C in row.
- [This video](dance_60_15_sync_max_dch.mp4) shows a simple dance motion of the Dance_ES set in the first row. The agents trained with AltConf and additional movements of the dance category. We show the results of H+2C in row 2 and H+4C in row.
- [This video](dance_05_05_sync_max_dch.mp4) shows a complex motion of the Dance_ES set in the first row. The agents trained with AltConf and additional movements of the dance category. We show the results of H+2C in row 2 and H+4C in row.
- [This video](dance_019-Relaxed-3-mirror-x-1-0_sync_max_dch.mp4) shows a conversation motion of the Basic_ES set in the first row. The agents trained with AltConf and additional movements of the dance category. We show the results of H+2C in row 2 and H+4C in row.

- [This video](jump_83_49_sync_max_dch.mp4) shows a jumping motion of the Jump_ES set in the first row. The agents trained with AltConf and additional movements of the jump category. We show the results of H+2C in row 2 and H+4C in row.
- [This video](jump_jumps1_subject1_sync_max_dch.mp4) shows a jumping motion of the LAFAN_Jump_ES set in the first row. The agents trained with AltConf and additional movements of the jump category. We show the results of H+2C in row 2 and H+4C in row.
- [This video](jump_dataset-2_walk-turn-right_normal_030_sync_max_dch.mp4) shows a walkingg motion of the Basic_ES set in the first row. The agents trained with AltConf and additional movements of the jump category. We show the results of H+2C in row 2 and H+4C in row.


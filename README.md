<html>
  <body>
    <h2>Survey on the Use of Classification Graphs in the Design of Energy-Efficient Memristor Crossbar Circuits</h2>
    <p>Memristors are two-terminal electronic devices whose resistance is affected by one or more internal state variables. Ohm's rule, which depends on the state, describes a memristor. Its resistance is determined by the applied voltage or current across the memristor's complete past signal waveform. Memristors have a lot of practical applications because they allow for the establishment of circuit features that resistors, capacitors and inductors cannot. Spintronic devices, ultra-dense information storage, neuromorphic circuits, and programmable electronics are examples of memristors' potential novel uses. Modern decision tree methods employ heuristics recursively to construct each split separately, which might not accurately capture the dataset's underlying characteristics. By building the complete decision tree at once to achieve global optimality, the optimal decision tree problem aims to solve this. In order to apply decision trees using flow-based computing, Pranav Sinha and Sunny Raj [1] propose an approach for designing in-memory, energy-efficient, and compact memristor crossbar circuits. They create a brand-new method called a binary classification graph, which is equally accurate to decision trees but makes choices based on bit values of input features rather than thresholds. Due to the use of sneak paths in computations, their suggested design is robust to manufacturing errors and can grow to large crossbar sizes. On various machine learning datasets, they train decision tree models, and then they produce crossbar designs that correlate to those models. They use SPICE models to check the accuracy of our designs and see how pre-existing hardware flaws affect the size of the memristor crossbars. They conclude by comparing the energy usage of our designs to those of other techniques, demonstrating that our approach outperforms cutting-edge designs in terms of energy efficiency and circuit size.<br>
      Designing circuits for implementing random forest by combining numerous crossbar arrays would be a straightforward extension of the work which I believe can be a scope of implementation here. Designing circuits for more intricate tree and graph neural networks and incorporating flow-based computing's robustness and low-energy utilization into neural networks would be a more ambitious course of action.</p><br>
      <h3>Bibliography:</h3>
      <p>When compared to other machine learning techniques, decision trees have a significant edge in terms of explanability and can perform well on a variety of datasets. For a variety of machine learning activities, including accelerating decision trees (DT) and neuromorphic computing, in-memory computing has been used. The proposed memristor-based LSTM circuit system was introduced using the extensively used for sentiment analysis IMDB dataset and SemEval dataset [2]. An appealing option for extreme power efficiency is in-memory computing and DL accelerators built on memristors. The implementation of power-efficient in-memory computing, DL accelerators, and spiking neural networks could be achieved with the help of memristors, a new beyond-complementary metal-oxide-semiconductor (CMOS) technology that is reviewed in this article [3]. A novel analog content addressable memory (CAM) based on developing memristor devices was suggested by Pedretti et al. [4] for quick look-up table operations. Here, they suggest using the analog CAM as an in-memory algorithmic primitive to accelerate tree-based model inference. The fundamental energy efficiency constraints of digital logic are modified by memristor crossbar circuits, which can execute analog matrix-vector multiplications. For a select few neural network applications, they have been demonstrated to perform well in specialized accelerators. Ankit et al. [6] introduce the Programmable Ultra-efficient Memristor Based Accelerator (PUMA), which improves memristor crossbars with general purpose execution units to allow the acceleration of a broad variety of Machine Learning (ML) inference workloads.</p><br>
      <h4>Reference:</h4>
      [1] Sinha, P. and Raj, S., 2022, October. Designing Energy-Efficient Decision Tree Memristor Crossbar Circuits Using Binary Classification Graphs. In Proceedings of the 41st IEEE/ACM International Conference on Computer-Aided Design (pp. 1-9).<br>
      [2] Mehonic, A., Sebastian, A., Rajendran, B., Simeone, O., Vasilaki, E. and Kenyon, A.J., 2020. Memristors—From
      in-memory computing, deep learning acceleration, and spiking neural networks to the future of neuromorphic and
      bio-inspired computing. Advanced Intelligent Systems, 2(11), p.2000085.<br>
      [3] Soudry, D., Di Castro, D., Gal, A., Kolodny, A. and Kvatinsky, S., 2015. Memristor-based multilayer neural
      networks with online gradient descent training. IEEE transactions on neural networks and learning systems, 26(10),
      pp.2408-2421.<br>
      [4] Pedretti, G., Graves, C.E., Serebryakov, S., Mao, R., Sheng, X., Foltin, M., Li, C. and Strachan, J.P., 2021. Tree-
      based machine learning performed in-memory with memristive analog CAM. Nature communications, 12(1),
      p.5806.<br>
      [5] Viswakumar, A., Ganganaik, P.B., Raj, P.M.P., Rao, B.P. and Kundu, S., 2021. Memristor-based in-memory
      processor for high precision semantic text classification. Computers & Electrical Engineering, 92, p.107160.<br>
      [6] Ankit, A., Hajj, I.E., Chalamalasetti, S.R., Ndu, G., Foltin, M., Williams, R.S., Faraboschi, P., Hwu, W.M.W.,
      Strachan, J.P., Roy, K. and Milojicic, D.S., 2019, April. PUMA: A programmable ultra-efficient memristor-based
      accelerator for machine learning inference. In Proceedings of the Twenty-Fourth International Conference on
      Architectural Support for Programming Languages and Operating Systems (pp. 715-731).<br>
      [7] Sze, V., Chen, Y.H., Yang, T.J. and Emer, J.S., 2017. Efficient processing of deep neural networks: A tutorial and
      survey. Proceedings of the IEEE, 105(12), pp.2295-2329<br>
      [8] Cavigelli, L., Gschwend, D., Mayer, C., Willi, S., Muheim, B. and Benini, L., 2015, May. Origami: A convolutional
      network accelerator. In Proceedings of the 25th edition on Great Lakes Symposium on VLSI (pp. 199-204).<br>
      [9] Gupta, S., Agrawal, A., Gopalakrishnan, K. and Narayanan, P., 2015, June. Deep learning with limited numerical
      precision. In International conference on machine learning (pp. 1737-1746). PMLR.<br>
      [10] Chen, T., Du, Z., Sun, N., Wang, J., Wu, C., Chen, Y. and Temam, O., 2014. Diannao: A small-footprint high-
      throughput accelerator for ubiquitous machine-learning. ACM SIGARCH Computer Architecture News, 42(1),
      pp.269-284.<br>
      [11] Chen, Y.H., Emer, J. and Sze, V., 2016. Eyeriss: A spatial architecture for energy-efficient dataflow for
      convolutional neural networks. ACM SIGARCH computer architecture news, 44(3), pp.367-379.<br>
      [12] Gao, M., Pu, J., Yang, X., Horowitz, M. and Kozyrakis, C., 2017, April. Tetris: Scalable and efficient neural
      network acceleration with 3d memory. In Proceedings of the Twenty-Second International Conference on
      Architectural Support for Programming Languages and Operating Systems (pp. 751-764).<br>
      [13] Wang, Z., Schapire, R. and Verma, N., 2014, May. Error-adaptive classifier boosting (EACB): Exploiting data-
      driven training for highly fault-tolerant hardware. In 2014 IEEE International Conference on Acoustics, Speech and
      Signal Processing (ICASSP) (pp. 3884-3888). IEEE.<br>
      [14] Ankit, A., Sengupta, A., Panda, P. and Roy, K., 2017, June. Resparc: A reconfigurable and energy-efficient
      architecture with memristive crossbars for deep spiking neural networks. In Proceedings of the 54th Annual Design
      Automation Conference 2017 (pp. 1-6).<br>
      [15] Ankit, A., Sengupta, A. and Roy, K., 2017, November. TraNNsformer: Neural network transformation for
      memristive crossbar based neuromorphic system design. In 2017 IEEE/ACM International Conference on
      Computer-Aided Design (ICCAD) (pp. 533-540). IEEE.<br>
      [16] Bojnordi, M.N. and Ipek, E., 2016, March. Memristive boltzmann machine: A hardware accelerator for
      combinatorial optimization and deep learning. In 2016 IEEE International Symposium on High Performance
      Computer Architecture (HPCA) (pp. 1-13). IEEE.<br>
      [17] Cheng, M., Xia, L., Zhu, Z., Cai, Y., Xie, Y., Wang, Y. and Yang, H., 2017, June. Time: A training-in-memory
      architecture for memristor-based deep neural networks. In Proceedings of the 54th Annual Design Automation
      Conference 2017 (pp. 1-6).<br>
      [18] Chi, P., Li, S., Xu, C., Zhang, T., Zhao, J., Liu, Y., Wang, Y. and Xie, Y., 2016. Prime: A novel processing-in-memory
      architecture for neural network computation in reram-based main memory. ACM SIGARCH Computer Architecture
      News, 44(3), pp.27-39.<br>
      [19] Shafiee, A., Nag, A., Muralimanohar, N., Balasubramonian, R., Strachan, J.P., Hu, M., Williams, R.S. and Srikumar, V., 2016. ISAAC: A convolutional neural network accelerator with in-situ analog arithmetic in crossbars. ACM SIGARCH Computer Architecture News, 44(3), pp.14-26.<br>
      [20] Song, L., Qian, X., Li, H. and Chen, Y., 2017, February. Pipelayer: A pipelined reram-based accelerator for deep learning. In 2017 IEEE international symposium on high performance computer architecture (HPCA) (pp. 541-552). IEEE.<br>
      [21] Fujiki, D., Mahlke, S. and Das, R., 2018. In-memory data parallel processor. ACM SIGPLAN Notices, 53(2), pp.1- 14.<br>
      [22] Farabet, C., Poulet, C., Han, J.Y. and LeCun, Y., 2009, August. Cnp: An fpga-based processor for convolutional networks. In 2009 International Conference on Field Programmable Logic and Applications (pp. 32-37). IEEE.<br>
      [23] Wang, Y., Xu, J., Han, Y., Li, H. and Li, X., 2016, June. DeepBurning: Automatic generation of FPGA-based learning accelerators for the neural network family. In Proceedings of the 53rd Annual Design Automation Conference (pp. 1-6).<br>
      [24] Zhang, C., Li, P., Sun, G., Guan, Y., Xiao, B. and Cong, J., 2015, February. Optimizing FPGA-based accelerator design for deep convolutional neural networks. In Proceedings of the 2015 ACM/SIGDA international symposium on field-programmable gate arrays (pp. 161-170).IEEE.<br>
      [25] Feinberg, B., Wang, S. and Ipek, E., 2018, February. Making memristive neural network accelerators reliable.
      In 2018 IEEE International Symposium on High Performance Computer Architecture (HPCA) (pp. 52-65). IEEE.<br>
      [26] Peemen, M., Setio, A.A., Mesman, B. and Corporaal, H., 2013, October. Memory-centric accelerator design for
      convolutional neural networks. In 2013 IEEE 31st international conference on computer design (ICCD) (pp. 13-19).<br>
      <center>__________________________</center>
  </body>
</html>

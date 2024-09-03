# **`RNNs: Use a single hidden state to carry information across time steps.`**
# **`LSTMs: Use both a hidden state and a cell state, with the cell state providing a more robust way to maintain long-term dependencies.`**

![image](https://github.com/user-attachments/assets/c34ca1eb-74b2-4be5-99cc-058585a37a51)

**`IN CASE OF LSTM, WE MAINTAIN BOTH THE STM AND LTM, ALSO TO ENABLE COMMUNICATION BETWEEN THEM, THE ARCHITECTURE BECOMES DIFFICULT AS COMPARED TO RNN'S`**
![image](https://github.com/user-attachments/assets/d983a350-53cf-46cd-87b5-9e97923ddef3)


# **`ARCHITECTURES`**
![image](https://github.com/user-attachments/assets/a5465805-1a0d-4fa8-811c-095f9c4102b5)


# **`LSTM GATES`**
![image](https://github.com/user-attachments/assets/9efab9c8-13c2-4a6e-8557-fcb1a1cc793a)


# **``SUMMARY**
* IT TAKES 3 THINGS AS INPUT, (current input, previous LTM (ct -1), previous STM (ht -1)) AND OUTPUTS, (new LTM (ct), and new STM (ht) for the next ones)
![image](https://github.com/user-attachments/assets/9fed1395-c488-43ae-980f-b9947dd73fac)

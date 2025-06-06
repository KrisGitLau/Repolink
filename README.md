
# 🧪 Repolink.ipynb - Missing Link Detection in BPMN Graphs

This Jupyter Notebook analyzes and compares BPMN-based process models (e.g., `.xpdl` or `.xml` files) to detect **missing links**, such as activities, transitions, associations, message flows, or data objects.

---

## 🔧 How to Run

1. **Install requirements** (if not already installed):

   ```bash
   pip install networkx matplotlib
   ```

2. **Open the notebook**:

   You can run it using:

   ```bash
   jupyter notebook Repolink.ipynb
   ```

3. **Set the target file**:

   Inside the notebook, look for this line:

   ```python
   target_file = 'XPDL Missing/your_target_file.xpdl'
   ```

   🔁 **To test a different XPDL**, just replace the file name, e.g.:

   ```python
   target_file = 'XPDL Missing/my_new_model.xpdl'
   ```

4. **Folder path is pre-set**:

   ```python
   folder_path = 'Dataset repositori'
   ```

   This means the notebook will search for other `.xpdl` or `.xml` files inside the `Dataset repositori` directory for comparison.

5. ⚠️ **If you rename/move folders or files**, make sure to **update `folder_path` and `target_file` in the code accordingly**.

---

## 📂 Expected Directory Layout

```
project-folder/
│
├── Repolink.ipynb
├── Dataset repositori/
│   ├── other_model1.xpdl
│   └── other_model2.xpdl
└── XPDL Missing/
    └── your_target_file.xpdl
```

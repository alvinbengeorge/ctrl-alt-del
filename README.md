# ctrl-alt-del
Project for Quantathon

# `Problem Statement:`
```
Given a Hamiltonian
0.00698131079425246 * IIIZ
-0.0004978294000830275 * IIZI
+4.664512584628966e-05 * IZII
+0.0004303465157577957 * ZIII
+0.5099539391488543 * IIZZ
+0.5099677387273946 * IZIZ
+0.5099488492845516 * IZZI
+0.5099106232913859 * ZIIZ
+0.5099467089998899 * ZIZI
+0.5099046167492709 * ZZII

and the ansatz
ry = TwoLocal(num_assets, "ry", "cz", reps=3, entanglement="full")

Find the following using SamplingVQE and EsimatorVQE for every step of the iteration

* Eigenstates, corresponding eigenvalues, and their probability.
* Also, extract the variational parameters associated with every step of the iteration.
```

# `Installation`

```sh
pip3 install -r requirements.txt
cd frontend
npm install
```

# `Backend`

```sh
# Deployment
uvicorn main:app

# Development
uvicorn main:app --reload
```

# `FrontEnd`

```sh
# Deployment
npm run build
npm start

# Development
npm run dev
```

# `Demo`
![image](https://github.com/alvinbengeorge/ctrl-alt-del/assets/84540554/e80a9f7c-faef-478a-8c2a-8f56138b6277)

![zmkOiyQR](https://github.com/alvinbengeorge/ctrl-alt-del/assets/84540554/cf3d13b2-06f7-4a56-8b75-7048a8f96eaf)

### Solving the problem statement

![Cr6Hy9pP](https://github.com/alvinbengeorge/ctrl-alt-del/assets/84540554/c2680dd9-d90f-46ab-a2c8-628919d39165)

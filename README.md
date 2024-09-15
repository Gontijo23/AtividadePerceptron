# AtividadePerceptron


def f(x, w, b):

    if len(x) == len(w):
        soma = sum(wi * xi for wi, xi in zip(w, x))
        return b + soma 
    else:
     print("O tamanho dos vetores x e w devem ser iguais.")


xn = [1, 2, 3 ]  
wn = [0.5, 0.3, 0.2]  
b = 2  

resultado = f(xn, wn, b)
print(resultado)

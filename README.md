# R first Step project
Using https://posit.cloud/ to study R.



# DailyStudy

![GitHub repo size](https://img.shields.io/github/repo-size/iuricode/README-template?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)



> Studying with Alura and devolop some solutions with R.

### Adjustments and improvements.

The project is still under development, and the upcoming updates will focus on the following tasks:

- [x] Advanced courses about R

The following tools were used in the construction of the project:

- [Posit Cloud](<https://posit.cloud/>)
- [R](<https://www.r-project.org/>)

Answer of the 1th project

1-)Create a vector with 3 rows
```R
minha_matriz <- matrix(c(1, 2, 3, 4, 5, 6, 7, 8, 9), nrow = 3, byrow = TRUE)
minha_matriz
```
2-)Create a vector and rename the col and row
```R
matriz_salarios <- matrix(c(8200, 4400, 3800, 6500, 2600, 3500, 7100, 9000, 5200), nrow = 3, byrow = TRUE)
nomes_linhas <- c("João", "Maria", "Pedro")
nomes_colunas <- c("Jan", "Fev", "Mar")
rownames(matriz_salarios) <- nomes_linhas
colnames(matriz_salarios) <- nomes_colunas

matriz_salarios

```
Answer of the 2th project

1-) Acess the third number in a list
```R
numeros <- c(10, 20, 30, 40, 50)
numeros[3]
```
2-)Sum numbers in R:
```R
colSums(minha_matriz)
```
3-) Add Col and Rows in matriz: cbind() and rbind()

4-) Create a table with 2 rows and 2 columns
```R
tabela <- matrix(c(1, 2, 3, 4), nrow = 2, byrow = TRUE)
```
5-) To assign names to the elements of the vector 
```R
names(nomes) <- c(‘Ana’, ‘Bob’, ‘Charlie’, ‘David’)
nomes <- c(‘Ana’, ‘Bob’, ‘Charlie’, ‘David’); names(nomes) <- nomes
```

Answer of the 3th project

1-)SUM two vectors and round the Result

```R
a <- c(1.5, 2.7, 3.2, 4.8)
b <- c(0.3, 1.1, 2.0, 1.5)
resultado <- round(sum(a, b))
resultado
```
2-) IF Else in R
```R
if (condicao) { codigo } else { outro_codigo }
```

3-)Use For to generate a result that differentiates between even and odd numbers
```R
for(i in 1:10){
if (i %% 2 == 0){
print("Par")
} else{
print("Impar")
}
}
```

4-)Implement a loop to accumulate daily sales until they reach 1000
```R
vendas_diarias <- c(120, 80, 150, 180, 100, 120, 130, 220)
total_vendas <- 0
indice <- 1
objetivo_vendas <- 1000

while (total_vendas < objetivo_vendas && indice <= length(vendas_diarias)) {
  total_vendas <- total_vendas + vendas_diarias[indice]
  print(paste("O total de vendas até agora é:", total_vendas))
  indice <- indice + 1
}

print(paste("Total de vendas final:", total_vendas))
```

Answer of the 4th project
1-) Create a vector with students rates and round this rates
```R
notas_alunos <- c(7.5, 8.0, 6.2, 9.1)
notas_alunos_arr <- round(notas_alunos)
notas_alunos_arr
```

2-) Math funcionts in R
abs() – Returns the absolute value of a number.
sqrt() – Returns the square root of a number.
mean() – Calculates the mean (average) of a numeric vector. While it is a statistical function, it can also be considered mathematical.

3-) Median of selected numbers
```R
numeros <- c(12, 8, 15, 7, 10, 14, 9)
mediana <- median(numeros)
mediana
```
4-)Max value of a selected numbers -> max(numeros)

Answer of the 5th project:

1-) Create a vector with the size P, M, G and using factor to add levels in this vector:
```R
size <- c("P", "M", "G")
size_different <- factor(size, levels = c("P", "M", "G"))
cat(as.character(size_different), "\n")
```

2-) Checking if `size_different` contains P:
```R
size <- c("P", "M", "G")
size_different <- factor(size, levels = c("P", "M", "G"))
contais_P <- "P" %in% size_different
contais_P
```

## 🤝 Creator

<table>
  <tr>
    <td align="center">
      <a href="#" title="Thales Farias">
        <img src="IMG_20230429_211838_511.jpg" width="100" alt="Foto do Thales Farias no GitHub"/><br>
        <sub>
          <b><a href="https://www.linkedin.com/in/thalesfreirefarias/" target="_blank">Thales Farias</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


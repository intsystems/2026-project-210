# Улучшение оценки нормы разности Гессианов при увеличении размера выборки

<!-- Change `kisnikser/m1p-template` to `intsystems/your-repository`-->
[![License](https://badgen.net/github/license/kisnikser/m1p-template?color=green)](https://github.com/kisnikser/m1p-template/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/kisnikser/m1p-template)](https://github.com/kisnikser/m1p-template/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/kisnikser/m1p-template.svg?color=0088ff)](https://github.com/kisnikser/m1p-template/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/kisnikser/m1p-template.svg?color=7f29d6)](https://github.com/kisnikser/m1p-template/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Name Surname </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Name Surname, PhD/DSc </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Name Surname, PhD/DSc </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper/main.pdf)
- [Slides](slides/main.pdf)

## Abstract

Исследование локальных свойств поверхности функции потерь, в частности поведения матрицы Гессе, является ключевой задачей для понимания сходимости нейросетей и оценки необходимого объема данных. В существующих работах оценка сходимости сводится к анализу нормы разности между матрицей Гессе на новом объекте и средней матрицей Гессе по предыдущей выборке. Текущий подход использует для этой оценки простое неравенство треугольника, что дает грубую константную верхнюю границу $2M_H$, не зависящую от размера выборки и не отражающую интуитивно ожидаемого убывания ошибки при росте $k$. Таким образом, проблема заключается в отсутствии теоретической оценки, которая описывала бы скорость убывания этой нормы.
Целью данной работы является вывод более точной верхней границы для нормы разности матриц Гессе, которая будет учитывать эффект усреднения и убывать с ростом количества наблюдений $k$. Для этого используется разложение разности через "популяционное среднее" и вводится предположения о концентрации пер-объектных матриц Гессе. Основным результатом станет получение оценки вида $O(\frac{1}{k})$ или $O(\frac{1}{\sqrt{k}})$ в зависимости от предположений с явными константами. Полученная теоретическая оценка будет подтверждена в экспериментах на задачах классификации изображений (MNIST, FashionMNIST, CIFAR10). 
Значимость исследования заключается в том, что улучшенная оценка позволит дать более строгое обоснование скорости сходимости оптимизационной поверхности, что является важным шагом для развития методов анализа достаточного размера обучающей выборки в глубоком обучении.

## Citation

If you find our work helpful, please cite us.
```BibTeX
@article{citekey,
    title={Title},
    author={Ignatiev Daniil, Nikita Kiselev (consultant), Andrey Grabovoy (advisor)},
    year={2025}
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.

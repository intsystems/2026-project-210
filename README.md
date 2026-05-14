# Улучшение оценки нормы разности гессианов для модели смеси экспертов

<!-- Change `kisnikser/m1p-template` to `intsystems/your-repository`-->
[![License](https://badgen.net/github/license/kisnikser/m1p-template?color=green)](https://github.com/kisnikser/m1p-template/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/kisnikser/m1p-template)](https://github.com/kisnikser/m1p-template/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/kisnikser/m1p-template.svg?color=0088ff)](https://github.com/kisnikser/m1p-template/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/kisnikser/m1p-template.svg?color=7f29d6)](https://github.com/kisnikser/m1p-template/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Ignatiev Daniil </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Nikita Kiselev, PhD/DSc </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Andrey Grabovoy, DSc </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper/main-2(15).pdf)
- [Slides](slides/final_talk.pdf)

## Abstract

Модель смеси экспертов (MoE) является эффективной архитектурой для масштабирования нейронных сетей, однако её локальные геометрические свойства, в частности структура матрицы Гессе, остаются малоизученными. В данной работе исследуется гаусс-ньютоновская компонента матрицы Гессе для модели MoE. Используя подход матрично-представимых сетей, разработанный ранее для полносвязных, сверточных и трансформерных архитектур, мы выводим явную верхнюю оценку спектральной нормы этой компоненты. Оценка выражается через нормы весов экспертов и гейтинга, нормы входных данных и архитектурные параметры (число экспертов, размерности слоев). Полученный результат позволяет анализировать влияние числа экспертов на кривизну поверхности функции потерь и может быть использован для изучения стабилизации ландшафта MoE при увеличении объема выборки. Экспериментальная валидация планируется на синтетических данных и задачах классификации.

**Ключевые слова:** смесь экспертов, матрица Гессе, гаусс-ньютоновское приближение, спектральная норма, матрично-представимые сети.

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

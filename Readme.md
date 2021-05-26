<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/AreaStep2DChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/AreaStep2DChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Step Area chart

The following example demonstrates how to create a [2D Step Area](https://docs.devexpress.com/WPF/9992/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/area-series/step-area?p=netframework) chart.

### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add an [AreaStepSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.AreaStepSeries2D?p=netframework) object with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection. 

Also, this example shows how to add a [chart title](https://docs.devexpress.com/WPF/7844/controls-and-libraries/charts-suite/chart-control/chart-elements/chart-titles?p=netframework).



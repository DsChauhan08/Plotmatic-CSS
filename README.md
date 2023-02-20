# PlotmaticCSS


**PlotmaticCSS is an open source CSS framework for data visualization.**

Visualization help end-users understand data. **PlotmaticCSS** help frontend developers turn data into beautiful charts and graphs using simple **CSS classes**.

No dependencies. 72kb file size. Less than 6kb gzipped file size!

## Documentation

Check the full documentation on [Plotmatic CSS](https://plotmaticcss.netlify.app/).

* [Get Started](https://plotmaticcss.netlify.app/docs/)
* [Components](https://plotmaticcss.netlify.app/components/)
* [Charts](https://plotmaticcss.netlify.app/charts/)
* [Customization](https://plotmaticcss.netlify.app/customization/)
* [Development](https://plotmaticcss.netlify.app/development/)
* [Examples](https://plotmaticcss.netlify.app/examples/)

## Installation

### CDN

Use [jsdelivr](https://www.jsdelivr.com/package/npm/PlotmaticCSS) CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/PlotmaticCSS/dist/charts.min.css">
```

Or [unpkg](https://unpkg.com/browse/PlotmaticCSS/) CDN:

```html
<link rel="stylesheet" href="https://unpkg.com/PlotmaticCSS/dist/charts.min.css">
```

### Package Manager

Install using [npm](https://www.npmjs.com/package/PlotmaticCSS):

```bash
npm install PlotmaticCSS
```

Or using [yarn](https://classic.yarnpkg.com/en/package/PlotmaticCSS):

```bash
yarn add PlotmaticCSS
```

## Usage

The data is structured using semantic HTML tags and styled using CSS classes which change the visual representation displayed to the end user.

```html
<table class="charts-css [ column ] [ show-primary-axis show-4-secondary-axes ] [ data-spacing-4 reverse-data ]">

  <caption> Front End Developer Salary </caption>

  <thead>
    <tr>
      <th scope="col"> Year </th>
      <th scope="col"> Income </th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <th scope="row"> 2016 </th>
      <td style="--size: calc( 40 / 100 );"> $ 40K </td>
    </tr>
    <tr>
      <th scope="row"> 2017 </th>
      <td style="--size: calc( 60 / 100 );"> $ 60K </td>
    </tr>
    <tr>
      <th scope="row"> 2018 </th>
      <td style="--size: calc( 75 / 100 );"> $ 75K </td>
    </tr>
    <tr>
      <th scope="row"> 2019 </th>
      <td style="--size: calc( 90 / 100 );"> $ 90K </td>
    </tr>
    <tr>
      <th scope="row"> 2020 </th>
      <td style="--size: calc( 100 / 100 );"> $ 100K <br> 👑 </td>
    </tr>
  </tbody>

</table>
```

The framework offers developers flexibility. You choose what components to display and how to style them. Each component offers several CSS classes and CSS variables to customizes your style.

The key feature is the ability to customize everything using basic CSS. Frontend developers can target any HTML element and customize it. This philosophical guideline is what makes the framework so flexible, easy and fun to use.

## Questions

For questions and support please use the [official forum](https://github.com/ChartsCSS/PlotmaticCSS/discussions) on GitHub.

## Liked PlotmaticCSS?

If you like the project, **please consider to star the repo on GitHub**.

Change the PlotmaticCSS to Plotmatic.css 

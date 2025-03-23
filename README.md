# BlazorPdf MAUI Hybrid Application

Demonstrates BlazorPdf working inside of a MAUI Blazor Hybrid application.

To get this to work in your project you will need to;

- Use [Gotho.BlazorPdf](https://www.nuget.org/packages/Gotho.BlazorPdf/1.0.2-alpha) version 1.0.2-alpha or greater
- Place this [pdf.worker.min.mjs](https://github.com/tgothorp/Gotho.BlazorPdf/blob/main/Gotho.BlazorPdf/wwwroot/pdf.worker.min.mjs) file in the top level of your project's wwwroot folder
- Set `UseProjectWorker="true"` when using the `PdfViewer` component

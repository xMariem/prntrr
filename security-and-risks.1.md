:::::::: {.relative .min-w-0 .flex-1 .mx-auto .max-w-screen-2xl .py-8 .break-anywhere .page-width-default .site-width-default .page-has-toc role="main"}
:::: {.max-w-3xl .page-width-wide:max-w-screen-2xl .mx-auto .mb-6 .space-y-3 .page-api-block:ml-0 .page-api-block:max-w-full .page-has-ancestors}
::: {.flex .h-fit .items-stretch .justify-start .overflow-hidden .*:translate-y-0! .*:shadow-none! .[&>*:not(:first-child)]:border-l-0 .[&>*:not(:first-child,:last-child)]:rounded-none! .[&>*:not(:only-child):first-child]:rounded-r-none .[&>*:not(:only-child):last-child]:rounded-l-none .float-right .ml-4 .xl:max-2xl:page-api-block:mr-62 .-my-1.5}
![](data:image/svg+xml;base64,PHN2ZyBzdHlsZT0ibWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL2NvcHkuc3ZnP3Y9MiZhbXA7dG9rZW49YTQ2MzkzNWU5Myk7LXdlYmtpdC1tYXNrLWltYWdlOnVybChodHRwczovL2thLXAuZm9udGF3ZXNvbWUuY29tL3JlbGVhc2VzL3Y2LjYuMC9zdmdzL3JlZ3VsYXIvY29weS5zdmc/dj0yJmFtcDt0b2tlbj1hNDYzOTM1ZTkzKTttYXNrLXJlcGVhdDpuby1yZXBlYXQ7LXdlYmtpdC1tYXNrLXJlcGVhdDpuby1yZXBlYXQ7bWFzay1wb3NpdGlvbjpjZW50ZXI7LXdlYmtpdC1tYXNrLXBvc2l0aW9uOmNlbnRlciIgY2xhc3M9ImdiLWljb24gYnV0dG9uLWxlYWRpbmctaWNvbiBzaXplLVsxZW1dIHNocmluay0wIj48L3N2Zz4=){.gb-icon
.button-leading-icon .size-[1em] .shrink-0}Copy

![](data:image/svg+xml;base64,PHN2ZyBzdHlsZT0ibWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL2NoZXZyb24tZG93bi5zdmc/dj0yJmFtcDt0b2tlbj1hNDYzOTM1ZTkzKTstd2Via2l0LW1hc2staW1hZ2U6dXJsKGh0dHBzOi8va2EtcC5mb250YXdlc29tZS5jb20vcmVsZWFzZXMvdjYuNi4wL3N2Z3MvcmVndWxhci9jaGV2cm9uLWRvd24uc3ZnP3Y9MiZhbXA7dG9rZW49YTQ2MzkzNWU5Myk7bWFzay1yZXBlYXQ6bm8tcmVwZWF0Oy13ZWJraXQtbWFzay1yZXBlYXQ6bm8tcmVwZWF0O21hc2stcG9zaXRpb246Y2VudGVyOy13ZWJraXQtbWFzay1wb3NpdGlvbjpjZW50ZXIiIGNsYXNzPSJnYi1pY29uIHNpemUtMyB0cmFuc2l0aW9uLXRyYW5zZm9ybSBncm91cC1kYXRhLVtzdGF0ZT1vcGVuXS9idXR0b246cm90YXRlLTE4MCI+PC9zdmc+){.gb-icon
.size-3 .transition-transform
.group-data-[state=open]/button:rotate-180}
:::

1.  [SECURITY &
    RISKS](security-and-risks.1.html){.decoration-[max(0.07em,1px)]
    .underline-offset-2 .links-accent:underline-offset-4
    .links-default:decoration-primary/6
    .links-default:text-primary-subtle
    .hover:links-default:text-primary-strong
    .contrast-more:links-default:text-primary
    .contrast-more:hover:links-default:text-primary-strong
    .links-accent:decoration-primary-subtle
    .hover:links-accent:decoration-[3px]
    .hover:links-accent:[text-decoration-skip-ink:none] .transition-all
    .duration-100 .no-underline .hover:underline .text-xs .tracking-wide
    .font-semibold .uppercase .flex .items-center .gap-1.5
    .contrast-more:underline .contrast-more:decoration-current}

# ![](data:image/svg+xml;base64,PHN2ZyBzdHlsZT0ibWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL3NoaWVsZC1jaGVjay5zdmc/dj0yJmFtcDt0b2tlbj1hNDYzOTM1ZTkzKTstd2Via2l0LW1hc2staW1hZ2U6dXJsKGh0dHBzOi8va2EtcC5mb250YXdlc29tZS5jb20vcmVsZWFzZXMvdjYuNi4wL3N2Z3MvcmVndWxhci9zaGllbGQtY2hlY2suc3ZnP3Y9MiZhbXA7dG9rZW49YTQ2MzkzNWU5Myk7bWFzay1yZXBlYXQ6bm8tcmVwZWF0Oy13ZWJraXQtbWFzay1yZXBlYXQ6bm8tcmVwZWF0O21hc2stcG9zaXRpb246Y2VudGVyOy13ZWJraXQtbWFzay1wb3NpdGlvbjpjZW50ZXIiIGNsYXNzPSJnYi1pY29uIHNpemUtWzFlbV0gdGV4dC10aW50LXN1YnRsZSBzaHJpbmstMCI+PC9zdmc+){.gb-icon .size-[1em] .text-tint-subtle .shrink-0}Audits {#audits .text-4xl .font-bold .flex .items-center .gap-4 .grow .text-pretty .clear-right .xs:clear-none}

We are protecting the trenches.
::::

::: {.grid .[&>*+*]:mt-5 .whitespace-pre-wrap}
Printr manages smart contracts across multiple chains to provide the
seamless experience you\'re getting on the app.

Smart contracts provide trustless automation, they\'re software systems
and they can be subject to inherent risks.

Smart contract risks are bugs or vulnerabilities in the contract code
that could result in unexpected behaviour or loss of funds. All
blockchain protocols have some smart contract risk, but best practices
can significantly mitigate these risks.

Printr is committed to security and we have implemented various measures
to enhance the safety of our smart contracts. While no system can be
entirely risk-free, we continuously work to improve security through
testing and best practices.

In this view, we\'ve audited our contracts with
[Ackee![](data:image/svg+xml;base64,PHN2ZyBzdHlsZT0ibWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL2Fycm93LXVwLXJpZ2h0LnN2Zz92PTImYW1wO3Rva2VuPWE0NjM5MzVlOTMpOy13ZWJraXQtbWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL2Fycm93LXVwLXJpZ2h0LnN2Zz92PTImYW1wO3Rva2VuPWE0NjM5MzVlOTMpO21hc2stcmVwZWF0Om5vLXJlcGVhdDstd2Via2l0LW1hc2stcmVwZWF0Om5vLXJlcGVhdDttYXNrLXBvc2l0aW9uOmNlbnRlcjstd2Via2l0LW1hc2stcG9zaXRpb246Y2VudGVyIiBjbGFzcz0iZ2ItaWNvbiBtbC0wLjUgaW5saW5lIHNpemUtMyBsaW5rcy1hY2NlbnQ6dGV4dC10aW50LXN1YnRsZSI+PC9zdmc+){.gb-icon
.ml-0.5 .inline .size-3
.links-accent:text-tint-subtle}](https://ackee.xyz/){.underline
.decoration-[max(0.07em,1px)] .underline-offset-2
.links-accent:underline-offset-4 .links-default:decoration-primary/6
.links-default:text-primary-subtle
.hover:links-default:text-primary-strong
.contrast-more:links-default:text-primary
.contrast-more:hover:links-default:text-primary-strong
.links-accent:decoration-primary-subtle
.hover:links-accent:decoration-[3px]
.hover:links-accent:[text-decoration-skip-ink:none] .transition-all
.duration-100}. You can confirm and scrutinise the results here.

\[Audit results coming soon\]
:::

::: {.flex .flex-col .md:flex-row .mt-6 .gap-2 .max-w-3xl .page-width-wide:max-w-screen-2xl .mx-auto .text-tint}
[[[Previous]{.text-xs}[Brand Kit]{.text-tint-strong
.group-hover:text-primary .line-clamp-2}]{.flex .flex-col .flex-1
.text-right}![](data:image/svg+xml;base64,PHN2ZyBzdHlsZT0ibWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL2NoZXZyb24tbGVmdC5zdmc/dj0yJmFtcDt0b2tlbj1hNDYzOTM1ZTkzKTstd2Via2l0LW1hc2staW1hZ2U6dXJsKGh0dHBzOi8va2EtcC5mb250YXdlc29tZS5jb20vcmVsZWFzZXMvdjYuNi4wL3N2Z3MvcmVndWxhci9jaGV2cm9uLWxlZnQuc3ZnP3Y9MiZhbXA7dG9rZW49YTQ2MzkzNWU5Myk7bWFzay1yZXBlYXQ6bm8tcmVwZWF0Oy13ZWJraXQtbWFzay1yZXBlYXQ6bm8tcmVwZWF0O21hc2stcG9zaXRpb246Y2VudGVyOy13ZWJraXQtbWFzay1wb3NpdGlvbjpjZW50ZXIiIGNsYXNzPSJnYi1pY29uIGhpZGRlbiBzaXplLTQgdGV4dC10aW50LXN1YnRsZSBjb250cmFzdC1tb3JlOnRleHQtdGludC1zdHJvbmcgZ3JvdXAtaG92ZXI6dGV4dC1wcmltYXJ5IG1kOmJsb2NrIj48L3N2Zz4=){.gb-icon
.hidden .size-4 .text-tint-subtle .contrast-more:text-tint-strong
.group-hover:text-primary .md:block}](community/brand-kit.html){.group
.text-sm .p-2.5 .flex .gap-4 .flex-1 .flex-row-reverse .items-center
.pl-4 .border .border-tint-subtle .rounded-sm
.circular-corners:rounded-2xl .straight-corners:rounded-none
.hover:border-primary .text-pretty .md:p-4
.md:text-base}[[[Next]{.text-xs}[Scams & Market
Manipulation]{.text-tint-strong .group-hover:text-primary
.line-clamp-2}]{.flex .flex-col
.flex-1}![](data:image/svg+xml;base64,PHN2ZyBzdHlsZT0ibWFzay1pbWFnZTp1cmwoaHR0cHM6Ly9rYS1wLmZvbnRhd2Vzb21lLmNvbS9yZWxlYXNlcy92Ni42LjAvc3Zncy9yZWd1bGFyL2NoZXZyb24tcmlnaHQuc3ZnP3Y9MiZhbXA7dG9rZW49YTQ2MzkzNWU5Myk7LXdlYmtpdC1tYXNrLWltYWdlOnVybChodHRwczovL2thLXAuZm9udGF3ZXNvbWUuY29tL3JlbGVhc2VzL3Y2LjYuMC9zdmdzL3JlZ3VsYXIvY2hldnJvbi1yaWdodC5zdmc/dj0yJmFtcDt0b2tlbj1hNDYzOTM1ZTkzKTttYXNrLXJlcGVhdDpuby1yZXBlYXQ7LXdlYmtpdC1tYXNrLXJlcGVhdDpuby1yZXBlYXQ7bWFzay1wb3NpdGlvbjpjZW50ZXI7LXdlYmtpdC1tYXNrLXBvc2l0aW9uOmNlbnRlciIgY2xhc3M9ImdiLWljb24gaGlkZGVuIHNpemUtNCB0ZXh0LXRpbnQtc3VidGxlIGNvbnRyYXN0LW1vcmU6dGV4dC10aW50LXN0cm9uZyBncm91cC1ob3Zlcjp0ZXh0LXByaW1hcnkgbWQ6YmxvY2siPjwvc3ZnPg==){.gb-icon
.hidden .size-4 .text-tint-subtle .contrast-more:text-tint-strong
.group-hover:text-primary
.md:block}](security-and-risks/scams-and-market-manipulation.html){.group
.text-sm .p-2.5 .flex .gap-4 .flex-1 .flex-row .items-center .pr-4
.border .border-tint-subtle .rounded-sm .circular-corners:rounded-2xl
.straight-corners:rounded-none .hover:border-primary .text-pretty
.md:p-4 .md:text-base}
:::

::: {.mx-auto .mt-6 .page-api-block:ml-0 .flex .max-w-3xl .page-full-width:max-w-screen-2xl .flex-row .flex-wrap .items-center .gap-4 .text-tint .contrast-more:text-tint-strong}
Last updated 2 months ago
:::
::::::::

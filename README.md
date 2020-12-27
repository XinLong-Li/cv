# Dongdong Tian's Curriculum Vitae

These are the LaTeX sources for my academic CV.

## Preview

Preview my CV:

- [English version](en/cv.pdf)
- [Chinese version (中文版)](cn/cv.pdf)

## Build

To build the CV, you need to have LaTeX installed. The full LaTeX distribution
(e.g., TeXLive on Linux, and MacTeX on macOS) are usually very big (>5 GB),
thus I recommend to install the lightweight [TinyTeX](https://yihui.org/tinytex/)
(< 100MB).

1. 	Install TinyTeX:

		curl -sL "https://yihui.org/tinytex/install-bin-unix.sh" | sh

2. 	Install LaTeX packages needed by the CV template:

    	tlmgr install anyfontsize datetime geometry enumitem xcolor fancyhdr \
			hyperref etaremune fmtcount sourcesanspro sourcecodepro ctex

3. 	Build the CV:

		make

## Acknowledgemnt

The CV template is modified from https://github.com/leouieda/cv.

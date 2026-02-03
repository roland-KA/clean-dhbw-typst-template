FROM mcr.microsoft.com/devcontainers/rust

ENV CARGO_REGISTRIES_CRATES_IO_PROTOCOL="sparse"
ENV TYPST_FONT_PATHS=/workspaces/Thesis-BPI/fonts

RUN cargo install --locked typst-cli


# Plataforma AI

<p align="center">
 <a href="#computer-sobre-o-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias-utilizadas">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#clipboard-pré-requisitos">Pré-requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## :computer: Sobre o projeto
Repositório com os casos de uso de aplicações AI.

## :rocket: Tecnologias utilizadas
As seguintes tecnologias foram usadas na construção do projeto:
- [OpenAI](https://openai.com/)
- [Flowise](https://flowiseai.com/)
- [Langfuse](https://langfuse.com/)
- [Redis](https://redis.io/)
- [Postgres](https://www.postgresql.org/)
- [PGVector](https://github.com/pgvector/pgvector)

OBS: Para aprendizado:
- [Huggingface](https://huggingface.co/)
- [Ollama](https://ollama.com/)
- [Webui Ollama](https://github.com/open-webui/open-webui)

## :clipboard: Pré-requisitos

Podemos fazer o pull via docker de todas as imagens.

```bash
$ docker pull postgres:latest
$ docker pull pgvector/pgvector:0.6.2-pg16
$ docker pull flowiseai/flowise:latest
$ docker pull ghcr.io/langfuse/langfuse:latest
$ docker pull redis:latest
```

OBS: Para aprendizado:
```bash
$ docker pull ollama/ollama:latest
$ docker pull ghcr.io/ollama-webui/ollama-webui:main
```
---

<p align="center" style="margin-top: 20px; border-top: 1px solid #eee; padding-top: 20px;">Feito por <strong> Futura Squad AI </strong> </p>

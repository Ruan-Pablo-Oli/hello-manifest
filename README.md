# Repositório de manifestos Kubernetes — hello-manifest

Este repositório armazena os manifestos Kubernetes (`deployment.yaml` e `service.yaml`) necessários para o deploy da aplicação `hello-app`.

## 🤖 Propósito (GitOps)

Este repositório segue o fluxo GitOps: a árvore Git é a fonte da verdade para os manifests de deploy. Um controlador (por exemplo, ArgoCD) pode monitorar este repositório e sincronizar automaticamente o estado desejado com o cluster Kubernetes.

---

### ⚠️ ATENÇÃO: repositório gerenciado automaticamente

Não edite os arquivos neste repositório manualmente.

Este repositório pode ser atualizado automaticamente por um pipeline de CI/CD (por exemplo, GitHub Actions) do repositório da aplicação (`hello-app`). A automação geralmente altera a tag da imagem no `deployment.yaml` sempre que uma nova versão é construída. Mudanças manuais podem ser sobrescritas.

---

## 📄 Arquivos

* **`deployment.yaml`** — define o Deployment do Kubernetes para a aplicação `hello-app`.
* **`service.yaml`** — define o Service que expõe a aplicação no cluster.

## 🔗 Repositório relacionado

* Repositório da aplicação (FastAPI + GitHub Actions):
  * `https://github.com/Ruan-Pablo-Oli/hello-app` (ou o link correto para o repositório da aplicação)


  
# cheerstag-gitops

GitOps repository for Cheerstag Application.

-   App manifests: \`apps/cheerstag-app/base\`
-   Argo CD Application: \`applications/cheerstag-app-dev.yaml\`

Next steps (after Argo CD is installed):

1. \`kubectl apply -n argocd -f applications/cheerstag-app-dev.yaml\`
2. Watch Argo sync the app into the \`cheerstag-app\` namespace.

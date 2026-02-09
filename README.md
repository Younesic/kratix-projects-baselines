# kratix-projects-baselines

Baselines versionnees pour les Promises Kratix.

- `baselines/namespace-bootstrap`: templates YAML pour NamespaceBootstrap (namespace, quotas, limitranges).
  - tailles: `small`, `standard`, `large`, `restricted`
- `baselines/namespace-access`: templates YAML pour NamespaceAccess (RBAC).
  - tailles: `standard` (fallback)

Chaque template est consomme a build-time par les images de pipeline Kratix.

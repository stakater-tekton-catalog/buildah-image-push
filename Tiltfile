settings = read_json('tilt-settings.json', default={})

if settings.get("allow_k8s_contexts"):
  allow_k8s_contexts(settings.get("allow_k8s_contexts"))

k8s_yaml(helm('./helm',name='stakater-buildah-image-push'))

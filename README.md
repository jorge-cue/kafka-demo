# Kafka Demo

This demo shows the way to fulfill the **livenessProve** and the **readinessProve**.

**readinessProve** is used by K8 and Openshift to verify that the pod is ready and can receive requests through its REST/SOAP API.

**livenessProve** is used by K8 and Openshift to verify that the pod has all its connections to downstream services alive, and therefore this por can do it's duty.


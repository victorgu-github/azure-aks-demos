# install keda 
helm repo add kedacore https://kedacore.github.io/charts
helm repo update
helm install keda kedacore/keda `
--create-namespace --namespace keda

# follow ps1 files to run the demo
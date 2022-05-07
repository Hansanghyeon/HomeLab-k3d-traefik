# HomeLab-k3d-traefik

## traefik dashboard (traefik-ingress.yaml)

k3d는 k3s 클러스터를 도커에 관리하고 k3s는 기본적으로 traefik이 내장되어있다.
traefik dashboard를 확인하기 위해서 traefik에 연결되는 ingress route를 활성화해준다.

## traefik https 강제 (traefik-https.yaml)

HelmChartConfig로 이루어진 traefik의 기본 설정값을 변경

## traefik let's encrypt (traefik-letsencrypt.yaml)

let's encrypt를 이용한 https 인증서 설정

## traefik tlsoption (traefik-tlsoption.yaml)

tls 옵션을 추가적으로 주어서 https 보안등급 up A+

https://www.ssllabs.com/ssltest/

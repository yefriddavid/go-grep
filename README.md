

go run main.go > "$(date +"%Y_%m_%d_%I_%M_%p").log"

go run main.go > "traze-log-filtered-$(date +"%Y_%m_%d_%I_%M").log"


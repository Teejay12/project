help:    ## Show this help.
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'

catalogue:	## install catalogue component for Roboshop project
	@sh components/catalogue.sh

cart:	## install cart component for Roboshop project
	@sh components/cart.sh

frontend:	## install frontend web component for Roboshop project
	@sh components/frontend.sh

mongodb:  ## install mongodb component for Roboshop project
	@sh components/mongodb.sh
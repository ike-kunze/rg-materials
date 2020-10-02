all:
ifdef v
	kramdown-rfc2629 version-$(v)/draft-kunze-coin-industrial-use-cases-$(v).mkd > version-$(v)/draft-kunze-coin-industrial-use-cases-$(v).xml
	xml2rfc version-$(v)/draft-kunze-coin-industrial-use-cases-$(v).xml
else
	@echo 'State version using v='
endif
	

.PHONY: clean
clean:
	rm draft-kunze-coin-industrial-use-cases-*.xml
デフォルトでは、{% ifversion ghes or ghae %}{% data variables.product.product_location %}上で有効化されると、{% data variables.product.prodname_actions %}{% elsif fpt %}{% data variables.product.prodname_actions %}{% endif %}はすべてのリポジトリとOrganizationで有効になります。 You can choose to disable {% data variables.product.prodname_actions %} or limit them to local actions only, which means that people can only use actions that exist in your repository.
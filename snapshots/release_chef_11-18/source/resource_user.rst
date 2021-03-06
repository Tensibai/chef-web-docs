.. THIS PAGE DOCUMENTS chef-client version 11.18

=====================================================
user
=====================================================

.. include:: ../../includes_resources/includes_resource_user.rst

Syntax
=====================================================
.. include:: ../../includes_resources/includes_resource_user_syntax_11-16.rst

Actions
=====================================================
.. include:: ../../includes_resources/includes_resource_user_actions.rst

Properties
=====================================================
.. include:: ../../includes_resources/includes_resource_user_attributes_11-16.rst

Password Shadow Hash
=====================================================
.. include:: ../../includes_resources/includes_resource_user_password_shadow_hash.rst

Providers
=====================================================
.. include:: ../../includes_resources_common/includes_resources_common_provider.rst

.. include:: ../../includes_resources_common/includes_resources_common_provider_attributes.rst

.. include:: ../../includes_resources/includes_resource_user_providers.rst

Examples
=====================================================
The following examples demonstrate various approaches for using resources in recipes. If you want to see examples of how Chef uses resources in recipes, take a closer look at the cookbooks that Chef authors and maintains: https://github.com/chef-cookbooks.

**Create a user named "random"**

.. include:: ../../step_resource/step_resource_user_create_random.rst

**Create a system user**

.. include:: ../../step_resource/step_resource_user_create_system.rst

**Create a system user with a variable**

.. include:: ../../step_resource/step_resource_user_create_system_user_with_variable.rst

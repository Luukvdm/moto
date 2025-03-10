.. _implementedservice_sagemaker:

.. |start-h3| raw:: html

    <h3>

.. |end-h3| raw:: html

    </h3>

=========
sagemaker
=========

|start-h3| Example usage |end-h3|

.. sourcecode:: python

            @mock_sagemaker
            def test_sagemaker_behaviour:
                boto3.client("sagemaker")
                ...



|start-h3| Implemented features for this service |end-h3|

- [ ] add_association
- [X] add_tags
- [X] associate_trial_component
- [ ] batch_describe_model_package
- [ ] create_action
- [ ] create_algorithm
- [ ] create_app
- [ ] create_app_image_config
- [ ] create_artifact
- [ ] create_auto_ml_job
- [ ] create_code_repository
- [ ] create_compilation_job
- [ ] create_context
- [ ] create_data_quality_job_definition
- [ ] create_device_fleet
- [ ] create_domain
- [ ] create_edge_deployment_plan
- [ ] create_edge_deployment_stage
- [ ] create_edge_packaging_job
- [X] create_endpoint
- [X] create_endpoint_config
- [X] create_experiment
- [ ] create_feature_group
- [ ] create_flow_definition
- [ ] create_hub
- [ ] create_human_task_ui
- [ ] create_hyper_parameter_tuning_job
- [ ] create_image
- [ ] create_image_version
- [ ] create_inference_experiment
- [ ] create_inference_recommendations_job
- [ ] create_labeling_job
- [X] create_model
- [ ] create_model_bias_job_definition
- [ ] create_model_card
- [ ] create_model_card_export_job
- [ ] create_model_explainability_job_definition
- [ ] create_model_package
- [ ] create_model_package_group
- [ ] create_model_quality_job_definition
- [ ] create_monitoring_schedule
- [X] create_notebook_instance
- [X] create_notebook_instance_lifecycle_config
- [X] create_pipeline
- [ ] create_presigned_domain_url
- [ ] create_presigned_notebook_instance_url
- [X] create_processing_job
- [ ] create_project
- [ ] create_space
- [ ] create_studio_lifecycle_config
- [X] create_training_job
- [ ] create_transform_job
- [X] create_trial
- [X] create_trial_component
- [ ] create_user_profile
- [ ] create_workforce
- [ ] create_workteam
- [ ] delete_action
- [ ] delete_algorithm
- [ ] delete_app
- [ ] delete_app_image_config
- [ ] delete_artifact
- [ ] delete_association
- [ ] delete_code_repository
- [ ] delete_context
- [ ] delete_data_quality_job_definition
- [ ] delete_device_fleet
- [ ] delete_domain
- [ ] delete_edge_deployment_plan
- [ ] delete_edge_deployment_stage
- [X] delete_endpoint
- [X] delete_endpoint_config
- [X] delete_experiment
- [ ] delete_feature_group
- [ ] delete_flow_definition
- [ ] delete_hub
- [ ] delete_hub_content
- [ ] delete_human_task_ui
- [ ] delete_image
- [ ] delete_image_version
- [ ] delete_inference_experiment
- [X] delete_model
- [ ] delete_model_bias_job_definition
- [ ] delete_model_card
- [ ] delete_model_explainability_job_definition
- [ ] delete_model_package
- [ ] delete_model_package_group
- [ ] delete_model_package_group_policy
- [ ] delete_model_quality_job_definition
- [ ] delete_monitoring_schedule
- [X] delete_notebook_instance
- [X] delete_notebook_instance_lifecycle_config
- [X] delete_pipeline
- [ ] delete_project
- [ ] delete_space
- [ ] delete_studio_lifecycle_config
- [X] delete_tags
- [X] delete_trial
- [X] delete_trial_component
- [ ] delete_user_profile
- [ ] delete_workforce
- [ ] delete_workteam
- [ ] deregister_devices
- [ ] describe_action
- [ ] describe_algorithm
- [ ] describe_app
- [ ] describe_app_image_config
- [ ] describe_artifact
- [ ] describe_auto_ml_job
- [ ] describe_code_repository
- [ ] describe_compilation_job
- [ ] describe_context
- [ ] describe_data_quality_job_definition
- [ ] describe_device
- [ ] describe_device_fleet
- [ ] describe_domain
- [ ] describe_edge_deployment_plan
- [ ] describe_edge_packaging_job
- [X] describe_endpoint
- [X] describe_endpoint_config
- [X] describe_experiment
- [ ] describe_feature_group
- [ ] describe_feature_metadata
- [ ] describe_flow_definition
- [ ] describe_hub
- [ ] describe_hub_content
- [ ] describe_human_task_ui
- [ ] describe_hyper_parameter_tuning_job
- [ ] describe_image
- [ ] describe_image_version
- [ ] describe_inference_experiment
- [ ] describe_inference_recommendations_job
- [ ] describe_labeling_job
- [ ] describe_lineage_group
- [X] describe_model
- [ ] describe_model_bias_job_definition
- [ ] describe_model_card
- [ ] describe_model_card_export_job
- [ ] describe_model_explainability_job_definition
- [ ] describe_model_package
- [ ] describe_model_package_group
- [ ] describe_model_quality_job_definition
- [ ] describe_monitoring_schedule
- [ ] describe_notebook_instance
- [X] describe_notebook_instance_lifecycle_config
- [ ] describe_pipeline
- [ ] describe_pipeline_definition_for_execution
- [ ] describe_pipeline_execution
- [X] describe_processing_job
- [ ] describe_project
- [ ] describe_space
- [ ] describe_studio_lifecycle_config
- [ ] describe_subscribed_workteam
- [X] describe_training_job
- [ ] describe_transform_job
- [X] describe_trial
- [X] describe_trial_component
- [ ] describe_user_profile
- [ ] describe_workforce
- [ ] describe_workteam
- [ ] disable_sagemaker_servicecatalog_portfolio
- [X] disassociate_trial_component
- [ ] enable_sagemaker_servicecatalog_portfolio
- [ ] get_device_fleet_report
- [ ] get_lineage_group_policy
- [ ] get_model_package_group_policy
- [ ] get_sagemaker_servicecatalog_portfolio_status
- [ ] get_search_suggestions
- [ ] import_hub_content
- [ ] list_actions
- [ ] list_algorithms
- [ ] list_aliases
- [ ] list_app_image_configs
- [ ] list_apps
- [ ] list_artifacts
- [ ] list_associations
- [ ] list_auto_ml_jobs
- [ ] list_candidates_for_auto_ml_job
- [ ] list_code_repositories
- [ ] list_compilation_jobs
- [ ] list_contexts
- [ ] list_data_quality_job_definitions
- [ ] list_device_fleets
- [ ] list_devices
- [ ] list_domains
- [ ] list_edge_deployment_plans
- [ ] list_edge_packaging_jobs
- [ ] list_endpoint_configs
- [ ] list_endpoints
- [X] list_experiments
- [ ] list_feature_groups
- [ ] list_flow_definitions
- [ ] list_hub_content_versions
- [ ] list_hub_contents
- [ ] list_hubs
- [ ] list_human_task_uis
- [ ] list_hyper_parameter_tuning_jobs
- [ ] list_image_versions
- [ ] list_images
- [ ] list_inference_experiments
- [ ] list_inference_recommendations_job_steps
- [ ] list_inference_recommendations_jobs
- [ ] list_labeling_jobs
- [ ] list_labeling_jobs_for_workteam
- [ ] list_lineage_groups
- [ ] list_model_bias_job_definitions
- [ ] list_model_card_export_jobs
- [ ] list_model_card_versions
- [ ] list_model_cards
- [ ] list_model_explainability_job_definitions
- [ ] list_model_metadata
- [ ] list_model_package_groups
- [ ] list_model_packages
- [ ] list_model_quality_job_definitions
- [X] list_models
- [ ] list_monitoring_alert_history
- [ ] list_monitoring_alerts
- [ ] list_monitoring_executions
- [ ] list_monitoring_schedules
- [ ] list_notebook_instance_lifecycle_configs
- [ ] list_notebook_instances
- [ ] list_pipeline_execution_steps
- [ ] list_pipeline_executions
- [ ] list_pipeline_parameters_for_execution
- [X] list_pipelines
- [X] list_processing_jobs
- [ ] list_projects
- [ ] list_spaces
- [ ] list_stage_devices
- [ ] list_studio_lifecycle_configs
- [ ] list_subscribed_workteams
- [X] list_tags
- [X] list_training_jobs
- [ ] list_training_jobs_for_hyper_parameter_tuning_job
- [ ] list_transform_jobs
- [X] list_trial_components
- [X] list_trials
- [ ] list_user_profiles
- [ ] list_workforces
- [ ] list_workteams
- [ ] put_model_package_group_policy
- [ ] query_lineage
- [ ] register_devices
- [ ] render_ui_template
- [ ] retry_pipeline_execution
- [X] search
- [ ] send_pipeline_execution_step_failure
- [ ] send_pipeline_execution_step_success
- [ ] start_edge_deployment_stage
- [ ] start_inference_experiment
- [ ] start_monitoring_schedule
- [X] start_notebook_instance
- [ ] start_pipeline_execution
- [ ] stop_auto_ml_job
- [ ] stop_compilation_job
- [ ] stop_edge_deployment_stage
- [ ] stop_edge_packaging_job
- [ ] stop_hyper_parameter_tuning_job
- [ ] stop_inference_experiment
- [ ] stop_inference_recommendations_job
- [ ] stop_labeling_job
- [ ] stop_monitoring_schedule
- [X] stop_notebook_instance
- [ ] stop_pipeline_execution
- [ ] stop_processing_job
- [ ] stop_training_job
- [ ] stop_transform_job
- [ ] update_action
- [ ] update_app_image_config
- [ ] update_artifact
- [ ] update_code_repository
- [ ] update_context
- [ ] update_device_fleet
- [ ] update_devices
- [ ] update_domain
- [ ] update_endpoint
- [X] update_endpoint_weights_and_capacities
- [ ] update_experiment
- [ ] update_feature_group
- [ ] update_feature_metadata
- [ ] update_hub
- [ ] update_image
- [ ] update_image_version
- [ ] update_inference_experiment
- [ ] update_model_card
- [ ] update_model_package
- [ ] update_monitoring_alert
- [ ] update_monitoring_schedule
- [ ] update_notebook_instance
- [ ] update_notebook_instance_lifecycle_config
- [X] update_pipeline
- [ ] update_pipeline_execution
- [ ] update_project
- [ ] update_space
- [ ] update_training_job
- [ ] update_trial
- [ ] update_trial_component
- [ ] update_user_profile
- [ ] update_workforce
- [ ] update_workteam


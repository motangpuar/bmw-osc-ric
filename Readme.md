
1. Generate the local helm chart 

    ```bash
    cd bin/
    ./install_common_templates_to_helm.sh
    ```

2. Install the generated components

    ```bash
    cd bin/
    ./install -f ../RECIPE_EXAMPLE/example_recipe_oran_i_release.yaml 

    ```

# nextflow

Default RIS Compute2 Nextflow Configuration

## Quick-Start

1. Overwrite default configuration in `$HOME`.
   ```bash
   mkdir -p $HOME/.config/nextflow/
   rm -rf $HOME/.config/nextflow/nextflow.config
   wget https://github.com/WashU-IT-RIS/c2-ris-app-config-templates/blob/main/nextflow/nextcloud.config -O $HOME/.config/nextflow/nextflow.config
   ```

1. Update the `cacheDir` path in `nextflow.config` with somewhere that exists and is owned by your user.
   ```
   vi $HOME/.config/nextflow/nextflow.config
   ```


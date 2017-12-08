HTTP Pack
=========

Please contribute a description :)

How To (very short)
-------------------

1. Clone [certifcationy-cli](https://github.com/certificationy/certificationy-cli)
2. Create or edit existing config (e.g. `http-config.yml`)

   ```yaml
   paths: ["../http-pack/data"] # or whereever this repository is
   ```

3. Load this config:

   ```sh
   $ php certificationy.php start --config=http-config.yml
   ```

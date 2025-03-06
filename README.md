# Mule Domain Sample
- Anypoint Studio
    1. Run as → Run configurations
    2. Select 2 applications projects (app1 & app2)
    3. Run project

- Mule Standalone
    1. Export 3 projects to jar files
        - Mule → Anypoint Studio Project to Mule Deployable Archive
    2. Copy domain jar to $MULE_HOME/domains
    3. Copy apps jars to $MULE_HOME/apps
        - Runtime manager is also available
    4. Run runtime
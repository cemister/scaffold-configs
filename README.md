# scaffold-configs
YAML templates for [Scaffolder](https://github.com/cemister/scaffolder)

## Usage
You can do it like this:
Linux:
```bash
# Replace cpp.yaml with needed config and hello to your actual project name
wget https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml && scaffold --name hello --yaml "./cpp.yaml" && rm cpp.yaml
```
macOS:
```bash
curl -O https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml && scaffold --name hello --yaml "./cpp.yaml" && rm cpp.yaml
```
Windows:
```bash
curl -o cpp.yaml https://raw.githubusercontent.com/cemister/scaffold-configs/master/cpp.yaml && scaffold --name hello --yaml "./cpp.yaml" && del cpp.yaml
```

Those are templates; feel free to fork this repo and modify them or make your own.

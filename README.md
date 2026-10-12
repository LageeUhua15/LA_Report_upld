*本项目旨在构建计算机体系结构研讨课实验报告（CA_LAB_REPORT）或模版*

# 目录说明
- `output/`：存放生成的实验报告模版与成品报告（含编译产物 PDF）
- `output/tamplate/`：当前实验报告模版（`tamplate.tex`、预览 `tamplate.pdf`、配图目录 `fig/`）
- `ucas_cod_lab_report_v10/`：计算机组成原理（研讨课）实验报告模版，仅作参照

# 创建完整实验报告
1. 检查工作区(`./output/tamplate/`)内是否有[实验报告模版文件](output/tamplate/tamplate.tex)。若无模版文件或模版文件内为空，则必须先创建模版文件。创建规则见[实验报告模版创建规则](TAMPLATE_GEN.md)
2. 根据[实验报告创建规则](REPORT_GEN.md)，编写完整实验报告内容

# 创建实验报告模版
1. 检查工作区(`./output/tamplate/`)内是否有[实验报告模版文件](output/tamplate/tamplate.tex)。若无模版文件或模版文件内为空，则直接创建模版文件。创建规则见[实验报告模版创建规则](TAMPLATE_GEN.md)
2. 若已有模版文件，则询问用户新模版文件是否覆盖、另存为或修改原有模版文件
3. 模版创建后需使用 XeLaTeX 编译验证，生成的 PDF 与模版文件放在同一目录下

<p align="center">
<a href="https://duckietown.com"><img src="./assets/images/dtlogo.png" alt="Duckietown Logo" width="50%"></a>
</p>

# **Learning Experience (LX): Lane Following**

# About these activities

This learning experience is designed to combine the knowledge we have gained from several of the simpler exercise into one more comlex lane following demo. 

It also serves as an introduction to the [`dts devel`](https://docs.duckietown.com/ente/duckietown-manual/70-developer-manual/dtproject/creating-demos.html) API which you can use to create new behaviors in Duckietown. 

This learning experience is provided by the Duckietown team and can be run on virtual and physical Duckiebots. Visit us at the 
[Duckietown Website](https://www.duckietown.com) for more learning materials, documentation, and demos.

For guided setup instructions, lecture content, and more related to this LX, see [the EdX course page](https://duckietown.com/self-driving-cars-with-duckietown-mooc/).


# Instructions

**NOTE:** All commands below are intended to be executed from the root directory of this exercise (i.e., the directory containing this README).


## 1. Make sure your exercise is up-to-date

Update your exercise definition and instructions,

    git pull upstream <your upstream branch>

**NOTE:** Example instructions to fork a repository and configure to pull from upstream can be found in the [duckietown-lx repository README](https://github.com/duckietown/duckietown-lx/blob/mooc2022/README.md).


**NEW FOR THIS LX**: You also need to clone the `dt-core` repository which is a "submodule" of this one. To do so execute:

    git submodule init
    git submodule update

You should now see the `dt-core` repo inside the `packages` folder. 

## 2. Make sure your system is up-to-date

- 💻 Always make sure your Duckietown Shell is updated to the latest version. See [installation instructions](https://github.com/duckietown/duckietown-shell)

- 💻 Update the shell commands: `dts update`

- 💻 Update your laptop/desktop: `dts desktop update`

- 🚙 Update your Duckiebot: `dts duckiebot update ROBOTNAME` (where `ROBOTNAME` is the name of your Duckiebot chosen during the initialization procedure.)


## 3. Work on the exercise

### Launch the code editor

Open the code editor by running the following command,

```
dts code editor
```

Wait for a URL to appear on the terminal, then click on it or copy-paste it in the address bar
of your browser to access the code editor. The first thing you will see in the code editor is
this same document, you can continue there.


### Walkthrough of notebooks

**NOTE**: You should be reading this from inside the code editor in your browser.

Inside the code editor, use the navigator sidebar on the left-hand side to navigate to the
`notebooks` directory and open the first notebook.

Follow the instructions on the notebook and work through the notebooks in sequence.


### Building and running your code

Different from previous learning experiences, we will not use the `dts code` API to 
build and run your code. Instead we will use a more flexible API that you can use for building further demos yourself, `dts devel`. You are a developer now!

This API is introduced in the [first notebook](./notebooks/00_DTS_devel_API.ipynb).

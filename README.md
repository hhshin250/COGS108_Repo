{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**If you lost points on the last checkpoint you can get them back by responding to TA/IA feedback**  \n",
    "\n",
    "Update/change the relevant sections where you lost those points, make sure you respond on GitHub Issues to your TA/IA to call their attention to the changes you made here.\n",
    "\n",
    "Please update your Timeline... no battle plan survives contact with the enemy, so make sure we understand how your plans have changed."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# COGS 108 - EDA Checkpoint"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Names\n",
    "\n",
    "- Ant Man\n",
    "- Hulk\n",
    "- Iron Man\n",
    "- Thor\n",
    "- Wasp"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Research Question"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "-  Include a specific, clear data science question.\n",
    "-  Make sure what you're measuring (variables) to answer the question is clear\n",
    "\n",
    "What is your research question? Include the specific question you're setting out to answer. This question should be specific, answerable with data, and clear. A general question with specific subquestions is permitted. (1-2 sentences)\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Background and Prior Work"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "\n",
    "- Include a general introduction to your topic\n",
    "- Include explanation of what work has been done previously\n",
    "- Include citations or links to previous work\n",
    "\n",
    "This section will present the background and context of your topic and question in a few paragraphs. Include a general introduction to your topic and then describe what information you currently know about the topic after doing your initial research. Include references to other projects who have asked similar questions or approached similar problems. Explain what others have learned in their projects.\n",
    "\n",
    "Find some relevant prior work, and reference those sources, summarizing what each did and what they learned. Even if you think you have a totally novel question, find the most similar prior work that you can and discuss how it relates to your project.\n",
    "\n",
    "References can be research publications, but they need not be. Blogs, GitHub repositories, company websites, etc., are all viable references if they are relevant to your project. It must be clear which information comes from which references. (2-3 paragraphs, including at least 2 references)\n",
    "\n",
    " **Use inline citation through HTML footnotes to specify which references support which statements** \n",
    "\n",
    "For example: After government genocide in the 20th century, real birds were replaced with surveillance drones designed to look just like birds.<a name=\"cite_ref-1\"></a>[<sup>1</sup>](#cite_note-1) Use a minimum of 2 or 3 citations, but we prefer more.<a name=\"cite_ref-2\"></a>[<sup>2</sup>](#cite_note-2) You need enough to fully explain and back up important facts. \n",
    "\n",
    "Note that if you click a footnote number in the paragraph above it will transport you to the proper entry in the footnotes list below.  And if you click the ^ in the footnote entry, it will return you to the place in the main text where the footnote is made.\n",
    "\n",
    "To understand the HTML here, `<a name=\"#...\"> </a>` is a tag that allows you produce a named reference for a given location.  Markdown has the construciton `[text with hyperlink](#named reference)` that will produce a clickable link that transports you the named reference.\n",
    "\n",
    "1. <a name=\"cite_note-1\"></a> [^](#cite_ref-1) Lorenz, T. (9 Dec 2021) Birds Aren’t Real, or Are They? Inside a Gen Z Conspiracy Theory. *The New York Times*. https://www.nytimes.com/2021/12/09/technology/birds-arent-real-gen-z-misinformation.html \n",
    "2. <a name=\"cite_note-2\"></a> [^](#cite_ref-2) Also refs should be important to the background, not some randomly chosen vaguely related stuff. Include a web link if possible in refs as above.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Hypothesis\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "\n",
    "- Include your team's hypothesis\n",
    "- Ensure that this hypothesis is clear to readers\n",
    "- Explain why you think this will be the outcome (what was your thinking?)\n",
    "\n",
    "What is your main hypothesis/predictions about what the answer to your question is? Briefly explain your thinking. (2-3 sentences)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Data"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Data overview\n",
    "\n",
    "For each dataset include the following information\n",
    "- Dataset #1\n",
    "  - Dataset Name:\n",
    "  - Link to the dataset:\n",
    "  - Number of observations:\n",
    "  - Number of variables:\n",
    "- Dataset #2 (if you have more than one!)\n",
    "  - Dataset Name:\n",
    "  - Link to the dataset:\n",
    "  - Number of observations:\n",
    "  - Number of variables:\n",
    "- etc\n",
    "\n",
    "Now write 2 - 5 sentences describing each dataset here. Include a short description of the important variables in the dataset; what the metrics and datatypes are, what concepts they may be proxies for. Include information about how you would need to wrangle/clean/preprocess the dataset\n",
    "\n",
    "If you plan to use multiple datasets, add a few sentences about how you plan to combine these datasets."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Dataset #1 (use name instead of number here)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "## YOUR CODE TO LOAD/CLEAN/TIDY/WRANGLE THE DATA GOES HERE\n",
    "## FEEL FREE TO ADD MULTIPLE CELLS PER SECTION "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Dataset #2 (if you have more than one, use name instead of number here)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "## YOUR CODE TO LOAD/CLEAN/TIDY/WRANGLE THE DATA GOES HERE\n",
    "## FEEL FREE TO ADD MULTIPLE CELLS PER SECTION "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Results\n",
    "\n",
    "## Exploratory Data Analysis\n",
    "\n",
    "Carry out whatever EDA you need to for your project.  Because every project will be different we can't really give you much of a template at this point. But please make sure you describe the what and why in text here as well as providing interpretation of results and context."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Section 1 of EDA - please give it a better title than this\n",
    "\n",
    "Some more words and stuff.  Remember notebooks work best if you interleave the code that generates a result with properly annotate figures and text that puts these results into context."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "## YOUR CODE HERE\n",
    "## FEEL FREE TO ADD MULTIPLE CELLS PER SECTION"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Section 2 of EDA if you need it  - please give it a better title than this\n",
    "\n",
    "Some more words and stuff.  Remember notebooks work best if you interleave the code that generates a result with properly annotate figures and text that puts these results into context."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "## YOUR CODE HERE\n",
    "## FEEL FREE TO ADD MULTIPLE CELLS PER SECTION"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Ethics & Privacy"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Thoughtful discussion of ethical concerns included\n",
    "- Ethical concerns consider the whole data science process (question asked, data collected, data being used, the bias in data, analysis, post-analysis, etc.)\n",
    "- How your group handled bias/ethical concerns clearly described\n",
    "\n",
    "Acknowledge and address any ethics & privacy related issues of your question(s), proposed dataset(s), and/or analyses. Use the information provided in lecture to guide your group discussion and thinking. If you need further guidance, check out [Deon's Ethics Checklist](http://deon.drivendata.org/#data-science-ethics-checklist). In particular:\n",
    "\n",
    "- Are there any biases/privacy/terms of use issues with the data you propsed?\n",
    "- Are there potential biases in your dataset(s), in terms of who it composes, and how it was collected, that may be problematic in terms of it allowing for equitable analysis? (For example, does your data exclude particular populations, or is it likely to reflect particular human biases in a way that could be a problem?)\n",
    "- How will you set out to detect these specific biases before, during, and after/when communicating your analysis?\n",
    "- Are there any other issues related to your topic area, data, and/or analyses that are potentially problematic in terms of data privacy and equitable impact?\n",
    "- How will you handle issues you identified?"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Team Expectations "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "\n",
    "Read over the [COGS108 Team Policies](https://github.com/COGS108/Projects/blob/master/COGS108_TeamPolicies.md) individually. Then, include your group’s expectations of one another for successful completion of your COGS108 project below. Discuss and agree on what all of your expectations are. Discuss how your team will communicate throughout the quarter and consider how you will communicate respectfully should conflicts arise. By including each member’s name above and by adding their name to the submission, you are indicating that you have read the COGS108 Team Policies, accept your team’s expectations below, and have every intention to fulfill them. These expectations are for your team’s use and benefit — they won’t be graded for their details.\n",
    "\n",
    "* *Team Expectation 1*\n",
    "* *Team Expectation 2*\n",
    "* *Team Expecation 3*\n",
    "* ..."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Project Timeline Proposal"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Specify your team's specific project timeline. An example timeline has been provided. Changes the dates, times, names, and details to fit your group's plan.\n",
    "\n",
    "If you think you will need any special resources or training outside what we have covered in COGS 108 to solve your problem, then your proposal should state these clearly. For example, if you have selected a problem that involves implementing multiple neural networks, please state this so we can make sure you know what you’re doing and so we can point you to resources you will need to implement your project. Note that you are not required to use outside methods.\n",
    "\n",
    "\n",
    "\n",
    "| Meeting Date  | Meeting Time| Completed Before Meeting  | Discuss at Meeting |\n",
    "|---|---|---|---|\n",
    "| 1/20  |  1 PM | Read & Think about COGS 108 expectations; brainstorm topics/questions  | Determine best form of communication; Discuss and decide on final project topic; discuss hypothesis; begin background research | \n",
    "| 1/26  |  10 AM |  Do background research on topic | Discuss ideal dataset(s) and ethics; draft project proposal | \n",
    "| 2/1  | 10 AM  | Edit, finalize, and submit proposal; Search for datasets  | Discuss Wrangling and possible analytical approaches; Assign group members to lead each specific part   |\n",
    "| 2/14  | 6 PM  | Import & Wrangle Data (Ant Man); EDA (Hulk) | Review/Edit wrangling/EDA; Discuss Analysis Plan   |\n",
    "| 2/23  | 12 PM  | Finalize wrangling/EDA; Begin Analysis (Iron Man; Thor) | Discuss/edit Analysis; Complete project check-in |\n",
    "| 3/13  | 12 PM  | Complete analysis; Draft results/conclusion/discussion (Wasp)| Discuss/edit full project |\n",
    "| 3/19  | Before 11:59 PM  | NA | Turn in Final Project & Group Project Surveys |"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "python3",
   "language": "python",
   "name": "python3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

<template>
    <section class="skills section" id="skills">
        <h2 class="section__title">Skills</h2>
        <span class="section__subtitle">My technical level</span>

        <div class="skills_container container grid">
            <div>
                <!--==================== SKILLS 1 ====================-->
                <div class="skills__content skills__open">
                    <div class="skills__header">
                        <i class="uil uil-brackets-curly skills__icon"></i>

                        <div>
                            <h1 class="skills__titles">Frontend developer</h1>
                            <span class="skills__subtitle">More than 2 years</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__list grid">
                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">HTML</h3>
                                <span class="skills__number">70%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__html"></span>
                            </div>
                        </div>

                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">CSS</h3>
                                <span class="skills__number">50%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__css"></span>
                            </div>
                        </div>

                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">JavaScript</h3>
                                <span class="skills__number">30%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__js"></span>
                            </div>
                        </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__vue"></span>
                            </div>
                        </div>
                    </div>
                </div>
            <div>
                <!--==================== SKILLS 3 ====================-->
                <div class="skills__content skills__close">
                    <div class="skills__header">
                        <i class="uil uil-swatchbook skills__icon"></i>

                        <div>
                            <h1 class="skills__titles">Designer</h1>
                            <span class="skills__subtitle">More than 3 years</span>
                        </div>

                        <i class="uil uil-angle-down skills__arrow"></i>
                    </div>

                    <div class="skills__list grid">
                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">Adobe Premiere Pro</h3>
                                <span class="skills__number">80%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__figma"></span>
                            </div>
                        </div>

                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">Adobe XD</h3>
                                <span class="skills__number">50%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__adobe"></span>
                            </div>
                        </div>

                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">Photoshop</h3>
                                <span class="skills__number">85%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__photoshop"></span>
                            </div>
                        </div>

                        <div class="skills__data">
                            <div class="skills__titles">
                                <h3 class="skills_name">Corel Draw</h3>
                                <span class="skills__number">40%</span>
                            </div>
                            <div class="skills__bar">
                                <span class="skills__percentage skills__corel"></span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Skills'
}

</script>
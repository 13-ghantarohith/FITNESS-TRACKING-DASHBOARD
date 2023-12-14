# FITNESS-TRACKING-DASHBOARD
<body>
    <div class="admin">
        <header class="admin__header">
            <div class="logo"><img src="https://ozcanzaferayan.github.io/fitness-admin-panel-css-grid/img/logo.png" />
                <span>Urban GYM</span></div>
            <nav class="navContainer">
                <div class="search">
                    <i class="fas fa-search"></i>
                    <input type="text" placeholder="Search..." />
                </div>
                <a class="link active" href="#">Dashboard</a>
                <a class="link" href="#">Schedule</a>
                <a class="link" href="#">Trainers</a>
                <a class="link" href="#">Customers</a>
                <div class="userContainer">
                    <div class="notifications">
                        <i class="far fa-bell"></i>
                    </div>
                    <div class="user">
                        <div class="img"></div>
                        <span class="name">Rohith Ghanta</span>
                        <i class="caret fas fa-angle-down"></i>
                    </div>
                </div>
            </nav>
        </header>
        <aside class="admin__aside">
            <div class="tabContainer">
                <div class="tabButton"><span>Location</span><i class="caret fas fa-angle-up"></i></div>
                <div class="tabButtonBorder"></div>
                <div class="panel">
                    <ul>
                        <li><input type="checkbox" /><span>vijayawada</span> </li>
                        <li><input type="checkbox" /><span>krishna</span> </li>
                        <li><input type="checkbox" /><span>Andhra Pradesh</span> </li>
                        <li><input type="checkbox" /><span>INDIA</span> </li>
                    </ul>
                </div>
            </div>
            <div class="tabContainer">
                <div class="tabButton"><span>Type of skills</span><i class="caret fas fa-angle-up"></i></div>
                <div class="tabButtonBorder"></div>
                <div class="panel">
                    <ul>
                        <li><input type="checkbox" /><span>Crossfit</span> </li>
                        <li><input type="checkbox" /><span>TRX</span> </li>
                        <li><input type="checkbox" /><span>Yoga</span> </li>
                        <li><input type="checkbox" /><span>Box</span> </li>
                    </ul>
                </div>
            </div>
            <div class="tabContainer">
                <div class="tabButton"><span>By reviews</span><i class="caret fas fa-angle-up"></i></div>
                <div class="tabButtonBorder"></div>
                <div class="panel">
                    <ul>
                        <li>
                            <input type="radio" name="star" checked /><span>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star"></i> & Up</span>
                        </li>
                        <li>
                            <input type="radio" name="star" /><span>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i> & Up</span>
                        </li>
                        <li>
                            <input type="radio" name="star" /><span>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i> & Up</span>
                        </li>
                        <li>
                            <input type="radio" name="star" /><span>
                            <i class="fa fa-star active"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i>
                            <i class="fa fa-star"></i> & Up</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="tabContainer">
                <div class="tabButton"><span>Customer base</span><i class="caret fas fa-angle-up"></i></div>
                <div class="tabButtonBorder"></div>
                <div class="panel">
                    <ul>
                        <li><input type="checkbox" /><span>İstanbul</span> </li>
                        <li><input type="checkbox" /><span>Ankara</span> </li>
                        <li><input type="checkbox" /><span>İzmir</span> </li>
                        <li><input type="checkbox" /><span>Balıkesir</span> </li>
                    </ul>
                </div>
            </div>
        </aside>
        <main class="admin__main">
            <div class="upgradeAccount">
                <img class="person girl" src="https://ozcanzaferayan.github.io/fitness-admin-panel-css-grid/img/girl.png" alt="">
                <span class="upgradeAccount__text__header">Looking for some upgrades?</span>
                <span class="upgradeAccount__text__description">Make whole management even more effective and enjoyable. Upgrade your profile to use the service to the best advantage. Let us help you enjoy more of what you do.</span>
                <div class="upgradeAccount__text__button">
                    <img class="effect-before" src="https://ozcanzaferayan.github.io/fitness-admin-panel-css-grid/img/buttonEffect.png" alt="">
                    <a href="#">Upgrade Account</a>
                    <img class="effect-after" src="https://ozcanzaferayan.github.io/fitness-admin-panel-css-grid/img/buttonEffect.png" alt="">
                </div>
                <img class="person boy" src="https://ozcanzaferayan.github.io/fitness-admin-panel-css-grid/img/boy.png" alt="">
                <div id="closeAlert" class="close">
                    <a href="#"><i class="fa fa-times"></i></a></div>
            </div>
            <div class="searchResultsHeader">
                <span>Found 6 trainers</span>
                <div class="layoutContainer">
                    <a class="table active" href="#"><i class="fas fa-table"></i></a>
                    <a class="list" href="#"><i class="fas fa-list"></i></a>
                </div>
            </div>
            <div class="searchResults">
                <div class="card">
                    <div class="user">
                        <div class="img"></div>
                        <div class="nameAndStars">
                            <div class="name">Jane Anderson</div>
                            <div class="stars">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                        </div>
                        <div class="options">
                            <i class="fas fa-ellipsis-v"></i>
                        </div>
                    </div>
                    <div class="skills">
                        <span class="header">Skills</span>
                        <div class="skillsContainer">
                            <a href="#" class="skill">Crossfit</a>
                            <a href="#" class="skill">TRX</a>
                            <a href="#" class="skill">Yoga</a>
                        </div>
                    </div>
                    <hr class="seperator" />
                    <div class="customers">
                        <span class="header">Customers</span>
                        <div class="customersContainer">
                            <img src="https://i.pravatar.cc/50?img=1" />
                            <img src="https://i.pravatar.cc/50?img=2" />
                            <img src="https://i.pravatar.cc/50?img=3" />
                            <img src="https://i.pravatar.cc/50?img=4" />
                            <img src="https://i.pravatar.cc/50?img=5" />
                        </div>

                    </div>
                    <hr class="seperator" />
                    <div class="activity">
                        <div class="headerContainer">
                            <span class="header">Activity</span>
                            <select>
                                <option value="Today">Today</option>
                                <option value="Tomorrow">Tomorrow</option>
                                <option value="Toyota">Toyota</option>
                            </select>
                        </div>
                        <div class="chartContainer">
                            <canvas id="activityChart1"></canvas>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="user">
                        <div class="img"></div>
                        <div class="nameAndStars">
                            <div class="name">Jane Anderson</div>
                            <div class="stars">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                        </div>
                        <div class="options">
                            <i class="fas fa-ellipsis-v"></i>
                        </div>
                    </div>
                    <div class="skills">
                        <span class="header">Skills</span>
                        <div class="skillsContainer">
                            <a href="#" class="skill">Crossfit</a>
                            <a href="#" class="skill">TRX</a>
                            <a href="#" class="skill">Yoga</a>
                        </div>
                    </div>
                    <hr class="seperator" />
                    <div class="customers">
                        <span class="header">Customers</span>
                        <div class="customersContainer">
                            <img src="https://i.pravatar.cc/50?img=1" />
                            <img src="https://i.pravatar.cc/50?img=2" />
                            <img src="https://i.pravatar.cc/50?img=3" />
                            <img src="https://i.pravatar.cc/50?img=4" />
                            <img src="https://i.pravatar.cc/50?img=5" />
                        </div>

                    </div>
                    <hr class="seperator" />
                    <div class="activity">
                        <div class="headerContainer">
                            <span class="header">Activity</span>
                            <select>
                                <option value="Today">Today</option>
                                <option value="Tomorrow">Tomorrow</option>
                                <option value="Toyota">Toyota</option>
                            </select>
                        </div>
                        <div class="chartContainer">
                            <canvas id="activityChart2"></canvas>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="user">
                        <div class="img"></div>
                        <div class="nameAndStars">
                            <div class="name">Jane Anderson</div>
                            <div class="stars">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                        </div>
                        <div class="options">
                            <i class="fas fa-ellipsis-v"></i>
                        </div>
                    </div>
                    <div class="skills">
                        <span class="header">Skills</span>
                        <div class="skillsContainer">
                            <a href="#" class="skill">Crossfit</a>
                            <a href="#" class="skill">TRX</a>
                            <a href="#" class="skill">Yoga</a>
                        </div>
                    </div>
                    <hr class="seperator" />
                    <div class="customers">
                        <span class="header">Customers</span>
                        <div class="customersContainer">
                            <img src="https://i.pravatar.cc/50?img=1" />
                            <img src="https://i.pravatar.cc/50?img=2" />
                            <img src="https://i.pravatar.cc/50?img=3" />
                            <img src="https://i.pravatar.cc/50?img=4" />
                            <img src="https://i.pravatar.cc/50?img=5" />
                        </div>

                    </div>
                    <hr class="seperator" />
                    <div class="activity">
                        <div class="headerContainer">
                            <span class="header">Activity</span>
                            <select>
                                <option value="Today">Today</option>
                                <option value="Tomorrow">Tomorrow</option>
                                <option value="Toyota">Toyota</option>
                            </select>
                        </div>
                        <div class="chartContainer">
                            <canvas id="activityChart3"></canvas>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="user">
                        <div class="img"></div>
                        <div class="nameAndStars">
                            <div class="name">Jane Anderson</div>
                            <div class="stars">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                        </div>
                        <div class="options">
                            <i class="fas fa-ellipsis-v"></i>
                        </div>
                    </div>
                    <div class="skills">
                        <span class="header">Skills</span>
                        <div class="skillsContainer">
                            <a href="#" class="skill">Crossfit</a>
                            <a href="#" class="skill">TRX</a>
                            <a href="#" class="skill">Yoga</a>
                        </div>
                    </div>
                    <hr class="seperator" />
                    <div class="customers">
                        <span class="header">Customers</span>
                        <div class="customersContainer">
                            <img src="https://i.pravatar.cc/50?img=1" />
                            <img src="https://i.pravatar.cc/50?img=2" />
                            <img src="https://i.pravatar.cc/50?img=3" />
                            <img src="https://i.pravatar.cc/50?img=4" />
                            <img src="https://i.pravatar.cc/50?img=5" />
                        </div>

                    </div>
                    <hr class="seperator" />
                    <div class="activity">
                        <div class="headerContainer">
                            <span class="header">Activity</span>
                            <select>
                                <option value="Today">Today</option>
                                <option value="Tomorrow">Tomorrow</option>
                                <option value="Toyota">Toyota</option>
                            </select>
                        </div>
                        <div class="chartContainer">
                            <canvas id="activityChart4"></canvas>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="user">
                        <div class="img"></div>
                        <div class="nameAndStars">
                            <div class="name">Jane Anderson</div>
                            <div class="stars">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                        </div>
                        <div class="options">
                            <i class="fas fa-ellipsis-v"></i>
                        </div>
                    </div>
                    <div class="skills">
                        <span class="header">Skills</span>
                        <div class="skillsContainer">
                            <a href="#" class="skill">Crossfit</a>
                            <a href="#" class="skill">TRX</a>
                            <a href="#" class="skill">Yoga</a>
                        </div>
                    </div>
                    <hr class="seperator" />
                    <div class="customers">
                        <span class="header">Customers</span>
                        <div class="customersContainer">
                            <img src="https://i.pravatar.cc/50?img=1" />
                            <img src="https://i.pravatar.cc/50?img=2" />
                            <img src="https://i.pravatar.cc/50?img=3" />
                            <img src="https://i.pravatar.cc/50?img=4" />
                            <img src="https://i.pravatar.cc/50?img=5" />
                        </div>

                    </div>
                    <hr class="seperator" />
                    <div class="activity">
                        <div class="headerContainer">
                            <span class="header">Activity</span>
                            <select>
                                <option value="Today">Today</option>
                                <option value="Tomorrow">Tomorrow</option>
                                <option value="Toyota">Toyota</option>
                            </select>
                        </div>
                        <div class="chartContainer">
                            <canvas id="activityChart5"></canvas>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="user">
                        <div class="img"></div>
                        <div class="nameAndStars">
                            <div class="name">Jane Anderson</div>
                            <div class="stars">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                        </div>
                        <div class="options">
                            <i class="fas fa-ellipsis-v"></i>
                        </div>
                    </div>
                    <div class="skills">
                        <span class="header">Skills</span>
                        <div class="skillsContainer">
                            <a href="#" class="skill">Crossfit</a>
                            <a href="#" class="skill">TRX</a>
                            <a href="#" class="skill">Yoga</a>
                        </div>
                    </div>
                    <hr class="seperator" />
                    <div class="customers">
                        <span class="header">Customers</span>
                        <div class="customersContainer">
                            <img src="https://i.pravatar.cc/50?img=1" />
                            <img src="https://i.pravatar.cc/50?img=2" />
                            <img src="https://i.pravatar.cc/50?img=3" />
                            <img src="https://i.pravatar.cc/50?img=4" />
                            <img src="https://i.pravatar.cc/50?img=5" />
                        </div>

                    </div>
                    <hr class="seperator" />
                    <div class="activity">
                        <div class="headerContainer">
                            <span class="header">Activity</span>
                            <select>
                                <option value="Today">Today</option>
                                <option value="Tomorrow">Tomorrow</option>
                                <option value="Toyota">Toyota</option>
                            </select>
                        </div>
                        <div class="chartContainer">
                            <canvas id="activityChart6"></canvas>
                        </div>
                    </div>
                </div>
            </div>
        </main>
        <footer class="admin__footer">
            <a class="link active" href="#"><i class="fa fa-home"></i><span>Dashboard</span></a>
            <a class="link" href="#"><i class="fa fa-calendar"></i><span>Schedule</span></a>
            <a class="link" href="#"><i class="fas fa-chalkboard-teacher"></i><span>Trainers</span></a>
            <a class="link" href="#"><i class="fa fa-users"></i><span>Customers</span></a>
        </footer>
    </div>

</body>
